---
title: "Methode get_resource_filter"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt einen Filter-String zurück, um nach Cache-Einträgen zu suchen, die Resource-Objekte darstellen."
type: docs
url: /de/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Gibt einen Filter‑String zurück, um nach Cache‑Einträgen zu suchen, die [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) Objekte darstellen.

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Seitenzahl. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `page_number` kleiner oder gleich null ist. |

### Siehe auch
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
