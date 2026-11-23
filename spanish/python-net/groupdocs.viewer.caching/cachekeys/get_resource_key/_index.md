---
title: "método get_resource_key"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve un identificador único para la entrada de caché que representa un objeto Resource."
type: docs
url: /es/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Devuelve un identificador único para la entrada de caché que representa el objeto [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de la página. |
| resource | `Resource` | El recurso HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `page_number` es menor o igual a cero, o si `resource` es None. |

### Ver también
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
