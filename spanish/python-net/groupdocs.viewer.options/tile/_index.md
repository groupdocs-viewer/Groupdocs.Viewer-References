---
title: "Clase Tile"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Representa la región de dibujo."
type: docs
url: /es/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Representa la región de dibujo.

Para más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

El tipo Tile expone los siguientes miembros:

### Constructores
| Constructor | Descripción |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Inicializa una instancia de la clase [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Métodos
| Método | Descripción |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Devuelve la coordenada X del punto más alto a la derecha del dibujo donde termina el tile. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Devuelve la coordenada Y del punto más alto a la derecha del dibujo donde termina el tile. |

### Propiedades
| Propiedad | Descripción |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | La altura del tile en píxeles. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | La coordenada X del punto más bajo a la izquierda del dibujo donde comienza el tile. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | La coordenada Y del punto más bajo a la izquierda del dibujo donde comienza el tile. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | El ancho del tile en píxeles. |

### Ejemplo

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

### Ver también
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
