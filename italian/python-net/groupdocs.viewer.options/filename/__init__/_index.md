---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza della classe FileName."
type: docs
url: /it/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Inizializza un'istanza della classe [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | `str` | Il nome del file. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `file_name` è None. |

### Esempio

```python
from groupdocs.viewer.options import FileName

# Crea un'istanza di FileName con un nome di archivio personalizzato
custom_name = FileName("Sample Files")
```

### Vedi anche
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
