---
title: "metodo get_resource_key"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Restituisce un identificatore unico per la voce della cache che rappresenta l'oggetto Resource."
type: docs
url: /it/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Restituisce un identificatore univoco per la voce della cache che rappresenta l'oggetto [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_number | `int` | Il numero della pagina. |
| resource | `Resource` | La risorsa HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `page_number` è minore o uguale a zero, o se `resource` è None. |

### Vedi anche
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
