---
title: "método get_page_key"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve un identificador único para la entrada de caché que representa el archivo de página."
type: docs
url: /es/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Devuelve un identificador único para la entrada de caché que representa el archivo de página.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| page_number | `int` | El número de la página. |
| extension | `str` | El sufijo del nombre de archivo (incluyendo el punto ".") p.ej. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `extension` es None o está vacío. |

### Ver también
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
