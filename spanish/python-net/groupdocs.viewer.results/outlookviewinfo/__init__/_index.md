---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de OutlookViewInfo."
type: docs
url: /es/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Inicializa una nueva instancia de OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo. |
| pages | `List[Page]` | La lista de páginas a visualizar. |
| folders | `List[str]` | La lista de carpetas contenidas en el archivo de datos de Outlook. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Lanzado cuando `folders` es None. |

### Ver también
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
