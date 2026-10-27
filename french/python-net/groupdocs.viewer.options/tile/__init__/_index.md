---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe Tile."
type: docs
url: /fr/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Initialise une instance de la classe [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Pour plus de détails, consultez la documentation.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| start_point_x | `int` | La coordonnée X du point le plus bas à gauche du dessin où la tuile commence. |
| start_point_y | `int` | La coordonnée Y du point le plus bas à gauche du dessin où la tuile commence. |
| width | `int` | La largeur de la tuile en pixels. |
| height | `int` | La hauteur de la tuile en pixels. |

### Exemple

```python
from groupdocs.viewer.options import Tile

# Définir les paramètres de la tuile
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Créer une tuile représentant une partie du dessin
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Voir aussi
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
