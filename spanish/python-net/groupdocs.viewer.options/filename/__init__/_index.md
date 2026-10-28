---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de la clase FileName."
type: docs
url: /es/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Inicializa una instancia de la clase [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | El nombre del archivo. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `file_name` es None. |

### Ejemplo

```python
from groupdocs.viewer.options import FileName

# Cree una instancia de FileName con un nombre de archivo personalizado
custom_name = FileName("Sample Files")
```

### Ver también
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
