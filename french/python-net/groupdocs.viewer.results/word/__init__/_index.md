---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de Word."
type: docs
url: /fr/python-net/groupdocs.viewer.results/word/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self):
    ...
```

## __init__ {#word-x-y-width-height-characters}

Initialise une nouvelle instance de [`Word`](/viewer/python-net/groupdocs.viewer.results/word/).

```python
def __init__(self, word, x, y, width, height, characters):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| word | `str` | Le mot. |
| x | `float` | La coordonnée X du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
| y | `float` | La coordonnée Y du point le plus haut à gauche de la mise en page où commence le rectangle contenant le mot. |
| width | `float` | La largeur du rectangle qui contient le mot. |
| height | `float` | La hauteur du rectangle qui contient le mot. |
| characters | `List[Character]` | Les caractères contenus par le mot. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `characters` est nul. |

### Voir aussi
* class [`Word`](/viewer/python-net/groupdocs.viewer.results/word/)
