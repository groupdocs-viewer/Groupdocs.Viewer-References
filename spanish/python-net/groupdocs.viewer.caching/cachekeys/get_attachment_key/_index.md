---
title: "método get_attachment_key"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Devuelve un identificador único para la entrada de caché que representa el archivo adjunto."
type: docs
url: /es/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Devuelve un identificador único para la entrada de caché que representa el archivo adjunto.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attachment_id | `str` | Identificador único (en el contexto de un solo archivo) del adjunto. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Lanzado cuando `attachment_id` es nulo o está vacío. |

### Ver también
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
