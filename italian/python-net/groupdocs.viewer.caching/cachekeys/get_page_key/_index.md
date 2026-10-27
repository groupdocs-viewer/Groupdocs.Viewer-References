---
title: "metodo get_page_key"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce un identificatore univoco per la voce della cache che rappresenta il file della pagina."
type: docs
url: /it/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Restituisce un identificatore univoco per la voce della cache che rappresenta il file della pagina.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero della pagina. |
| extension | `str` | Il suffisso del nome file (incluso il punto ".") es. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `extension` è None o vuoto. |

### Vedi anche
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
