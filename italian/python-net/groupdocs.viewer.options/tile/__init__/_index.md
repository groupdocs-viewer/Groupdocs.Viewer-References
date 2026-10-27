---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe Tile."
type: docs
url: /it/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Inizializza un'istanza della classe [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Per i dettagli, vedere la documentazione.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| start_point_x | `int` | La coordinata X del punto più basso a sinistra del disegno dove inizia la tile. |
| start_point_y | `int` | La coordinata Y del punto più basso a sinistra del disegno dove inizia la tile. |
| width | `int` | La larghezza della tile in pixel. |
| height | `int` | L'altezza della tile in pixel. |

### Esempio

```python
from groupdocs.viewer.options import Tile

# Definisci i parametri della tile
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Crea una tile che rappresenta una porzione del disegno
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Vedi anche
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
