---
title: "Classe Tile"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente la région de dessin."
type: docs
url: /fr/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Représente la région de dessin.

Pour plus de détails, consultez la documentation à l'adresse https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Le type Tile expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Initialise une instance de la classe [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Renvoie la coordonnée X du point le plus haut à droite du dessin où la tuile se termine. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Renvoie la coordonnée Y du point le plus haut à droite du dessin où la tuile se termine. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | La hauteur de la tuile en pixels. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | La coordonnée X du point le plus bas à gauche du dessin où la tuile commence. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | La coordonnée Y du point le plus bas à gauche du dessin où la tuile commence. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | La largeur de la tuile en pixels. |

### Exemple

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

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
