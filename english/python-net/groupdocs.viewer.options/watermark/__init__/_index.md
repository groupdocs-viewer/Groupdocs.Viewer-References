---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a Watermark instance."
type: docs
url: /python-net/groupdocs.viewer.options/watermark/__init__/
is_root: false
weight: 10
---


## __init__ {#text}

Initializes a Watermark instance.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Watermark text. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `text` is None or empty. |

### Example

```python
from groupdocs.viewer.options import Watermark

# Create a watermark with the desired text.
wm = Watermark("This is a watermark")
```

### See Also
* class [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/)
