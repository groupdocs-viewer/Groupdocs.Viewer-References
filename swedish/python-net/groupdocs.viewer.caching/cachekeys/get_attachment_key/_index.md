---
title: "get_attachment_key metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar en unik identifierare för cacheposten som representerar bilagafilen."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Returnerar en unik identifierare för cacheposten som representerar bilagafilen.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attachment_id | `str` | Unik (i kontext av en enda fil) identifierare för bilagan. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Kastas när `attachment_id` är null eller tom. |

### Se även
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
