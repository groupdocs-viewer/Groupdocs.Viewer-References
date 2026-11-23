---
title: "get_file_key-methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert een unieke identifier voor de cache‑entry die het bestand vertegenwoordigt."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Retourneert een unieke identifier voor de cache‑entry die het bestand vertegenwoordigt.

```python
def get_file_key(cls, extension):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extension | `str` | Het bestandsnaamsuffix (inclusief de punt "."), bijv. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `extension` None of leeg is. |

### Zie ook
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
