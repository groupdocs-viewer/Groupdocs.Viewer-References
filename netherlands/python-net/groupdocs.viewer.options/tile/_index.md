---
title: "Tile‑klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt het tekengebied voor."
type: docs
url: /nl/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Stelt het tekengebied voor.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Het Tile-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initialiseert een instantie van de [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) klasse. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Geeft de X‑coördinaat terug van het hoogste rechterpunt op de tekening waar de tegel eindigt. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Geeft de Y‑coördinaat terug van het hoogste rechterpunt op de tekening waar de tegel eindigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | De hoogte van de tegel in pixels. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | De X‑coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | De Y‑coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | De breedte van de tegel in pixels. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
