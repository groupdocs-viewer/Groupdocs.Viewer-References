---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de Resource."
type: docs
url: /fr/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de Resource.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Initialise une nouvelle instance de Resource.

```python
def __init__(self, file_name, nested):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Nom du fichier de ressource. |
| nested | `bool` | Indique si la ressource réside à l'intérieur d'une autre ressource, par ex. ressource de police qui réside dans une ressource CSS ou SVG. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `file_name` est None ou vide. |

### Voir aussi
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
