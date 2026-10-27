---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة من الفئة Watermark."
type: docs
url: /ar/python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

يُنشئ مثيلاً من الفئة [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/).

```python
def __init__(self, text):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| text | `str` | نص العلامة المائية. |

| يُثير | الوصف |
| :- | :- |
| `ValueError` | إذا كان `text` None أو فارغًا. |

### مثال

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

### انظر أيضًا
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
