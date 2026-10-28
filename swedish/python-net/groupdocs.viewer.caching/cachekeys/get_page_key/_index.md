---
title: "get_page_key metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar unik identifierare för cacheposten som representerar sidfilen."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Returnerar unik identifierare för cacheposten som representerar sidfilen.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |
| extension | `str` | Filnamnsuffixen (inklusive punkten ".") t.ex. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `extension` är None eller tom. |

### Se även
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
