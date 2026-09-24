---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the Watermark class."
type: docs
url: /python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Initializes an instance of the [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/) class.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Watermark text. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `text` is None or empty. |

### Example

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

### See Also
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
