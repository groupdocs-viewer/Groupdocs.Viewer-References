---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de CadViewInfo."
type: docs
url: /fr/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Initialise une nouvelle instance de CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_type | `FileType` | Le type du fichier. |
| pages | `List[Page]` | La liste des pages à afficher. |
| layers | `List[Layer]` | La liste des calques contenue dans le dessin CAD. |
| layouts | `List[Layout]` | La liste des calques contenue dans le dessin CAD. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Levée lorsque `layouts` est None. |

### Voir aussi
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
