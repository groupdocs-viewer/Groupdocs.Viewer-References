---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en instans av Tile-klassen."
type: docs
url: /sv/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initierar en instans av klassen [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

För detaljer, se dokumentationen.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| start_point_x | `int` | X-koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
| start_point_y | `int` | Y-koordinaten för den lägsta vänstra punkten på ritningen där plattan börjar. |
| width | `int` | Bredden på plattan i pixlar. |
| height | `int` | Höjden på plattan i pixlar. |

### Exempel

```python
from groupdocs.viewer.options import Tile

# Definiera tile-parametrar
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Skapa en tile som representerar en del av ritningen
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Se även
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
