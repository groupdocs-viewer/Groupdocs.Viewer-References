---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de CadViewInfo."
type: docs
url: /es/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Inicializa una nueva instancia de CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_type | `FileType` | El tipo del archivo. |
| pages | `List[Page]` | La lista de páginas a visualizar. |
| layers | `List[Layer]` | La lista de capas contenidas en el dibujo CAD. |
| layouts | `List[Layout]` | La lista de capas contenidas en el dibujo CAD. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Se lanza cuando `layouts` es None. |

### Ver también
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
