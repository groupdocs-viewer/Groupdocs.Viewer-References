---
title: "Methode get_attachment_key"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Anhangsdatei darstellt."
type: docs
url: /de/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Gibt einen eindeutigen Bezeichner für den Cache‑Eintrag zurück, der die Anhangsdatei darstellt.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attachment_id | `str` | Eindeutiger (im Kontext einer einzelnen Datei) Bezeichner des Anhangs. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wird ausgelöst, wenn `attachment_id` null oder leer ist. |

### Siehe auch
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
