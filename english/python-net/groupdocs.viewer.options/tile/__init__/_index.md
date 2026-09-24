---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes an instance of the Tile class."
type: docs
url: /python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initializes an instance of the [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) class.

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

# Define tile parameters
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Create a tile representing a portion of the drawing
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### See Also
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
