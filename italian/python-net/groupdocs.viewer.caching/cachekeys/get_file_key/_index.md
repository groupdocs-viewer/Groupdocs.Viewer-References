---
title: "metodo get_file_key"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce un identificatore univoco per la voce della cache che rappresenta il file."
type: docs
url: /it/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Restituisce un identificatore univoco per la voce della cache che rappresenta il file.

```python
def get_file_key(cls, extension):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extension | `str` | Il suffisso del nome file (incluso il punto ".") es. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `extension` è None o vuoto. |

### Vedi anche
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
