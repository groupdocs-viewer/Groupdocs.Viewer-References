---
title: "FileLogger 클래스"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "파일에 로그 메시지를 기록합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.logging/filelogger/
is_root: false
weight: 20
---


## FileLogger class

파일에 로그 메시지를 기록합니다.

FileLogger 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/filelogger/__init__/#file_name) | 파일에 메시지를 기록하는 로거를 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/filelogger/error/#message-exception) | 콘솔에 오류 메시지를 기록합니다. 오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace/#message) | 로그에 추적 메시지를 기록합니다. 추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning/#message) | 콘솔에 경고 메시지를 기록합니다. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/filelogger/warning_string/) |  |

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
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
