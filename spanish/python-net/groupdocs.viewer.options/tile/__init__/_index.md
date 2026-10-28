---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase Tile."
type: docs
url: /es/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Inicializa una instancia de la clase [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Para obtener más detalles, consulte la documentación.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| start_point_x | `int` | La coordenada X del punto más bajo a la izquierda del dibujo donde comienza el tile. |
| start_point_y | `int` | La coordenada Y del punto más bajo a la izquierda del dibujo donde comienza el tile. |
| width | `int` | El ancho del tile en píxeles. |
| height | `int` | La altura del tile en píxeles. |

### Ejemplo

```python
from groupdocs.viewer.options import Tile

# Definir parámetros del tile.
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Crear un tile que representa una parte del dibujo
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Ver también
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
