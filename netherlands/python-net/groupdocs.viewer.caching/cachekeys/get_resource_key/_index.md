---
title: "get_resource_key methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert een unieke identifier voor de cache‑entry die een Resource‑object vertegenwoordigt."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Retourneert een unieke identifier voor de cache‑entry die het [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) object vertegenwoordigt.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het nummer van de pagina. |
| resource | `Resource` | De HTML‑resource. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `page_number` kleiner of gelijk aan nul is, of als `resource` None is. |

### Zie ook
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
