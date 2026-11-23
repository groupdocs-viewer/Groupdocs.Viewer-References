---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een instantie van de Tile-klasse."
type: docs
url: /nl/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initialiseert een instantie van de [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) klasse.

Zie voor details de documentatie.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| start_point_x | `int` | De X‑coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| start_point_y | `int` | De Y‑coördinaat van het laagste linkerpunt op de tekening waar de tegel begint. |
| width | `int` | De breedte van de tegel in pixels. |
| height | `int` | De hoogte van de tegel in pixels. |

### Voorbeeld

```python
from groupdocs.viewer.options import Tile

# Definieer tegelparameters
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Maak een tegel die een deel van de tekening weergeeft
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Zie ook
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
