---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de ArchiveViewInfo."
type: docs
url: /es/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Inicializa una nueva instancia de ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo. |
| pages | `List[Page]` | La lista de páginas a visualizar. |
| folders | `List[str]` | La lista de carpetas contenidas en el archivo del archivo. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `folders` es None. |

### Ver también
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
