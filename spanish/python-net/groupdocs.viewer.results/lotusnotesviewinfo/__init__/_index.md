---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de LotusNotesViewInfo."
type: docs
url: /es/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Inicializa una nueva instancia de la clase [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo. |
| pages | `List[Page]` | La lista de páginas a visualizar. |
| notes_count | `int` | El recuento de notas contenido en el archivo de almacenamiento de la base de datos Lotus. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `notes_count` es None. |

### Ver también
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
