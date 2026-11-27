---
title: from_rgb method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Creates an Argb32Color value from the specified red, green, and blue channels, with the alpha channel set to fully opaque."
type: docs
url: /python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1040
---


## from_rgb {#red-green-blue}

Creates an [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) value from the specified red, green, and blue channels, with the alpha channel set to fully opaque.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| red | `int` | Red channel value. |
| green | `int` | Green channel value. |
| blue | `int` | Blue channel value. |

**Returns:** Argb32Color: New `Argb32Color` value.

### Example

```python
from groupdocs.viewer.drawing import Argb32Color

# Yellow color (RGB 255, 255, 0)
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### See Also
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
