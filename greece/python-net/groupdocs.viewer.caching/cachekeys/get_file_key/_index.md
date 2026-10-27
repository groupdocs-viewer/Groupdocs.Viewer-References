---
title: "μέθοδος get_file_key"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο."
type: docs
url: /el/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο.

```python
def get_file_key(cls, extension):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extension | `str` | Το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `extension` είναι None ή κενό. |

### Δείτε επίσης
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
