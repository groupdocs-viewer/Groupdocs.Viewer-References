---
title: "Methode get_file_key"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Datei darstellt."
type: docs
url: /de/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Datei darstellt.

```python
def get_file_key(cls, extension):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extension | `str` | Der Dateinamensuffix (einschließlich des Punktes "."), z. B. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `extension` None oder leer ist. |

### Siehe auch
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
