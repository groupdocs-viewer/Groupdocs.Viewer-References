---
title: "get_resource_filter metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Returnerar en filtersträng för att söka efter cacheposter som representerar Resource-objekt."
type: docs
url: /sv/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Returnerar en filtersträng för att söka efter cacheposter som representerar [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) objekt.

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page_number | `int` | Sidans antal. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `page_number` är mindre än eller lika med noll. |

### Se även
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
