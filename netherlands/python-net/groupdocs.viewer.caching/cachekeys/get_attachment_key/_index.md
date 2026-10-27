---
title: "get_attachment_key methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert een unieke identifier voor de cache‑entry die het bijlage‑bestand vertegenwoordigt."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Retourneert een unieke identifier voor de cache‑entry die het bijlage‑bestand vertegenwoordigt.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attachment_id | `str` | Unieke (in de context van één bestand) identifier van de attachment. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wordt gegooid wanneer `attachment_id` null of leeg is. |

### Zie ook
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
