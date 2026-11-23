---
title: "get_page_key methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Retourneert een unieke identifier voor de cache‑entry die het paginabestand vertegenwoordigt."
type: docs
url: /nl/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Retourneert een unieke identifier voor de cache‑entry die het paginabestand vertegenwoordigt.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| page_number | `int` | Het nummer van de pagina. |
| extension | `str` | Het bestandsnaamsuffix (inclusief de punt "."), bijv. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `extension` None of leeg is. |

### Zie ook
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
