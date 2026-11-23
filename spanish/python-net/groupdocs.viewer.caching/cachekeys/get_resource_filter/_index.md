---
title: "método get_resource_filter"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve una cadena de filtro para buscar entradas de caché que representan objetos Resource."
type: docs
url: /es/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Devuelve una cadena de filtro para buscar entradas de caché que representan objetos [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de página. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `page_number` es menor o igual a cero. |

### Ver también
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
