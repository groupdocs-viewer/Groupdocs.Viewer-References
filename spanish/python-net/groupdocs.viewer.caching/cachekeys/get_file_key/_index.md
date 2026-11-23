---
title: "método get_file_key"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve un identificador único para la entrada de caché que representa un archivo."
type: docs
url: /es/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Devuelve un identificador único para la entrada de caché que representa un archivo.

```python
def get_file_key(cls, extension):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| extension | `str` | El sufijo del nombre de archivo (incluyendo el punto ".") p.ej. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Si `extension` es None o está vacío. |

### Ver también
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
