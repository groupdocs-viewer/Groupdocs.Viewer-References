---
title: "get_resource_key metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar unik identifierare för cacheposten som representerar Resource‑objektet."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Returnerar unik identifierare för cacheposten som representerar [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) objekt.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans nummer. |
| resource | `Resource` | HTML‑resursen. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `page_number` är mindre än eller lika med noll, eller om `resource` är None. |

### Se även
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
