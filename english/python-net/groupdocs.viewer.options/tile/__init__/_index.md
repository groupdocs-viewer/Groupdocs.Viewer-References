---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a Tile instance."
type: docs
url: /python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initializes a Tile instance.

For details, see the documentation.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| start_point_x | `int` | The X coordinate of the lowest left point on the drawing where the tile begins. |
| start_point_y | `int` | The Y coordinate of the lowest left point on the drawing where the tile begins. |
| width | `int` | The width of the tile in pixels. |
| height | `int` | The height of the tile in pixels. |

### Example

```python
from groupdocs.viewer.options import Tile

# Create a tile covering a 200 × 200 pixel area starting at (0, 0)
tile = Tile(0, 0, 200, 200)
```

### See Also
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
