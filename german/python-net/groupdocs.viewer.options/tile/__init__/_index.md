---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine Instanz der Tile-Klasse."
type: docs
url: /de/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initialisiert eine Instanz der [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) Klasse.

Weitere Details finden Sie in der Dokumentation.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| start_point_x | `int` | Die X-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| start_point_y | `int` | Die Y-Koordinate des niedrigsten linken Punktes in der Zeichnung, an dem das Tile beginnt. |
| width | `int` | Die Breite des Kachels in Pixeln. |
| height | `int` | Die Höhe des Tiles in Pixeln. |

### Beispiel

```python
from groupdocs.viewer.options import Tile

# Tile-Parameter definieren
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Erstellen Sie ein Tile, das einen Teil der Zeichnung darstellt
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Siehe auch
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
