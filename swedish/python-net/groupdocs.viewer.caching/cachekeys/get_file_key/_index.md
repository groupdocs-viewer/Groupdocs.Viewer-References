---
title: "get_file_key metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar unik identifierare för cacheposten som representerar filen."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Returnerar unik identifierare för cacheposten som representerar filen.

```python
def get_file_key(cls, extension):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extension | `str` | Filnamnsuffixen (inklusive punkten ".") t.ex. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `extension` är None eller tom. |

### Se även
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
