---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de Line."
type: docs
url: /fr/python-net/groupdocs.viewer.results/line/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self):
    ...
```

## __init__ {#line-x-y-width-height-words}

Initialise une nouvelle instance de la classe [`Line`](/viewer/python-net/groupdocs.viewer.results/line/).

```python
def __init__(self, line, x, y, width, height, words):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| line | `str` | La ligne. |
| x | `float` | La coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle contenant la ligne. |
| y | `float` | La coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle contenant la ligne. |
| width | `float` | La largeur du rectangle qui contient la ligne (en pixels). |
| height | `float` | La hauteur du rectangle qui contient la ligne (en pixels). |
| words | `List[Word]` | Les mots contenus par la ligne. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `line` est nul ou vide, ou lorsque `words` est nul. |

### Voir aussi
* class [`Line`](/viewer/python-net/groupdocs.viewer.results/line/)
