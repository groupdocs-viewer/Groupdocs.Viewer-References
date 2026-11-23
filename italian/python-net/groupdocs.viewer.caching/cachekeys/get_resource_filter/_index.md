---
title: "metodo get_resource_filter"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce una stringa di filtro per cercare le voci della cache che rappresentano oggetti Resource."
type: docs
url: /it/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Restituisce una stringa di filtro per cercare le voci della cache che rappresentano oggetti [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero della pagina. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `page_number` è minore o uguale a zero. |

### Vedi anche
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
