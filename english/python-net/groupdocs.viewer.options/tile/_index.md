---
title: Tile class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents the drawing region."
type: docs
url: /python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Represents the drawing region.

For details, see the documentation.

The Tile type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initializes a Tile instance. |

### Methods
| Method | Description |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Returns the X coordinate of the highest right point on the drawing where the tile ends. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Returns the Y coordinate of the highest right point on the drawing where the tile ends. |

### Properties
| Property | Description |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | The height of the tile in pixels. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | The X coordinate of the lowest left point on the drawing where the tile begins. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | The Y coordinate of the lowest left point on the drawing where the tile begins. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | The width of the tile in pixels. |

### Example

```python
from groupdocs.viewer.options import Tile

# Create a tile that starts at (0, 0) and spans 500 × 500 units
tile = Tile(0, 0, 500, 500)

# The tile can be added to the viewer's CAD options
# view_options.cad_options.tiles.append(tile)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
