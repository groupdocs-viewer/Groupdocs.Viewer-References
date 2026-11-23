---
title: "get_resource_filter methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert een filter‑string om te zoeken naar cache‑entries die Resource‑objecten vertegenwoordigen."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Retourneert een filter‑string om te zoeken naar cache‑entries die [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) objecten vertegenwoordigen.

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het nummer van de pagina. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `page_number` kleiner of gelijk aan nul is. |

### Zie ook
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
