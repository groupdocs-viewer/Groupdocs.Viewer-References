---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance de la classe FileName."
type: docs
url: /fr/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Initialise une instance de la classe [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | `str` | Le nom du fichier. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `file_name` est None. |

### Exemple

```python
from groupdocs.viewer.options import FileName

# Créer une instance de FileName avec un nom d'archive personnalisé
custom_name = FileName("Sample Files")
```

### Voir aussi
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
