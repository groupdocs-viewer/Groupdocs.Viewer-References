---
title: "Tile-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt den Zeichenbereich dar."
type: docs
url: /de/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Stellt den Zeichenbereich dar.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Der Tile-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initialisiert eine Instanz der [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) Klasse. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Gibt die X-Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Gibt die Y-Koordinate des höchsten rechten Punktes in der Zeichnung zurück, an dem das Tile endet. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Die Höhe des Tiles in Pixeln. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | Die X-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Die Y-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Die Breite des Kachels in Pixeln. |

### Beispiel

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

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
