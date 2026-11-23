---
title: "Tile-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar ritområdet."
type: docs
url: /sv/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Representerar ritområdet.

För detaljer, se dokumentationen på https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Tile-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initierar en instans av klassen [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Returnerar X-koordinaten för den högsta högra punkten på ritningen där plattan slutar. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Returnerar Y-koordinaten för den högsta högra punkten på ritningen där plattan slutar. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Höjden på plattan i pixlar. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | X-koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Y-koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Bredden på plattan i pixlar. |

### Exempel

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

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
