---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "워드 프로세싱 문서를 렌더링하기 위한 옵션을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/
is_root: false
weight: 10
---


## __init__

워드 프로세싱 문서를 렌더링하기 위한 옵션을 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("document.docx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # 추적 변경 사항 렌더링을 활성화합니다.
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### 참고
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
