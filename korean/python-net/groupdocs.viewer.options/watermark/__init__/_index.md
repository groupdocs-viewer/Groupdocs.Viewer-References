---
title: "__init__ 생성자"
second_title: "GroupDocs.Viewer 용 Python via .NET API 참조"
description: "Watermark 클래스의 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

[`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) 클래스의 인스턴스를 초기화합니다.

```python
def __init__(self, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| text | `str` | 워터마크 텍스트. |

| 예외 발생 | 설명 |
| :- | :- |
| `ValueError` | `text`가 None이거나 비어 있는 경우. |

### 예시

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

with Viewer("sample.docx") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "add_text_watermark/output-watermark.html"
    )
    view_options.watermark = Watermark("This is a watermark")
    viewer.view(view_options)
```

### 참고
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
