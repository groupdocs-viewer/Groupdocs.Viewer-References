---
title: "Classe Tile"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta la regione di disegno."
type: docs
url: /it/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Rappresenta la regione di disegno.

Per i dettagli, consultare la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Il tipo Tile espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Inizializza un'istanza della classe [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Restituisce la coordinata X del punto più alto a destra del disegno dove termina la tile. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Restituisce la coordinata Y del punto più alto a destra del disegno dove termina la tile. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | L'altezza della tile in pixel. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | La coordinata X del punto più basso a sinistra del disegno dove inizia la tile. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | La coordinata Y del punto più basso a sinistra del disegno dove inizia la tile. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | La larghezza della tile in pixel. |

### Esempio

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

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
