---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일에 메시지를 기록하는 로거를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.logging/filelogger/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

파일에 메시지를 기록하는 로거를 초기화합니다.

```python
def __init__(self, file_name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | `str` | 전체 파일 경로와 이름. |

### 예시

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import FileLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=FileLogger("./log.txt"))
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "write_logs_to_file/page_{0}.html"
    )
    viewer.view(html_options)
```

### 참고
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
