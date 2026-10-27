---
title: "Methode get_resource_key"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt einen eindeutigen Bezeichner für den Cache-Eintrag zurück, der das Objekt Resource darstellt."
type: docs
url: /de/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der das [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/) Objekt darstellt.

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Seitenzahl. |
| resource | `Resource` | Die HTML-Ressource. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `page_number` kleiner oder gleich null ist oder `resource` None ist. |

### Siehe auch
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
