---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de Resource."
type: docs
url: /es/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de Resource.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Inicializa una nueva instancia de Resource.

```python
def __init__(self, file_name, nested):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | `str` | Nombre del archivo de recurso. |
| nested | `bool` | Indica si el recurso se encuentra dentro de otro recurso, p. ej. recurso de fuente que se encuentra en un recurso CSS o SVG. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se produce cuando `file_name` es None o está vacío. |

### Ver también
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
