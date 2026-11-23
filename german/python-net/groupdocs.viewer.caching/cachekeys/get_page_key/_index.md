---
title: "Methode get_page_key"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Seiten‑Datei darstellt."
type: docs
url: /de/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Seiten‑Datei darstellt.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| page_number | `int` | Die Seitenzahl. |
| extension | `str` | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `extension` None oder leer ist. |

### Siehe auch
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
