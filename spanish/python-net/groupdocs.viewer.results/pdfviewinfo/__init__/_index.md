---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de PdfViewInfo."
type: docs
url: /es/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de PdfViewInfo.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Inicializa una nueva instancia de PdfViewInfo.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo. |
| pages | `List[Page]` | La lista de páginas a visualizar. |
| printing_allowed | `bool` | El indicador de permiso de impresión. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `pages` es None. |

### Ver también
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
