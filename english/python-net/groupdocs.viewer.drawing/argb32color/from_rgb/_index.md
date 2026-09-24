---
title: from_rgb method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates an Argb32Color value from specified Red, Green, Blue channels, with the Alpha channel set to fully opaque."
type: docs
url: /python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Creates an Argb32Color value from specified Red, Green, Blue channels, with the Alpha channel set to fully opaque.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| red | `int` | Red channel value. |
| green | `int` | Green channel value. |
| blue | `int` | Blue channel value. |

**Returns:** Argb32Color: New Argb32Color value.

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### See Also
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
