---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una nueva instancia de FileCache."
type: docs
url: /es/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Inicializa una nueva instancia de FileCache.

```python
def __init__(self, cache_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cache_path | `str` | Ruta relativa o absoluta donde se almacenará la caché del documento. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `cache_path` es None. |

## __init__ {#cache_path-cache_sub_folder}

Inicializa una nueva instancia de la clase FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cache_path | `str` | Ruta relativa o absoluta donde se almacenará la caché del documento. |
| cache_sub_folder | `str` | La subcarpeta que se añadirá a `cache_path`. |

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `cache_sub_folder` es None. |

### Ver también
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
