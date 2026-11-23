---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di FileCache."
type: docs
url: /it/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Inizializza una nuova istanza di FileCache.

```python
def __init__(self, cache_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cache_path | `str` | Percorso relativo o assoluto dove verrà memorizzata la cache del documento. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `cache_path` è None. |

## __init__ {#cache_path-cache_sub_folder}

Inizializza una nuova istanza della classe FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cache_path | `str` | Percorso relativo o assoluto dove verrà memorizzata la cache del documento. |
| cache_sub_folder | `str` | La sottocartella da aggiungere a `cache_path`. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `cache_sub_folder` è None. |

### Vedi anche
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
