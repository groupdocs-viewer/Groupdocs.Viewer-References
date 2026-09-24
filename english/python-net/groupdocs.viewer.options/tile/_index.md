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

For details, see the documentation at https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

The Tile type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initializes an instance of the [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) class. |

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
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### See Also
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
