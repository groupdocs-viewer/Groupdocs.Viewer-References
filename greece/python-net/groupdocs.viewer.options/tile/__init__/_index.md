---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της κλάσης Tile."
type: docs
url: /el/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Για λεπτομέρειες, δείτε την τεκμηρίωση.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| start_point_x | `int` | Η συντεταγμένη X του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| start_point_y | `int` | Η συντεταγμένη Y του χαμηλότερου αριστερού σημείου στο σχέδιο όπου αρχίζει το tile. |
| width | `int` | Το πλάτος του tile σε εικονοστοιχεία. |
| height | `int` | Το ύψος του tile σε εικονοστοιχεία. |

### Παράδειγμα

```python
from groupdocs.viewer.options import Tile

# Ορίστε τις παραμέτρους του tile
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Δημιουργήστε ένα tile που αντιπροσωπεύει ένα τμήμα του σχεδίου
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Δείτε επίσης
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
