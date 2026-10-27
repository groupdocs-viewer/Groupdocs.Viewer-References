---
title: "get_page_key μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο σελίδας."
type: docs
url: /el/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο σελίδας.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός της σελίδας. |
| extension | `str` | Το επίθημα του ονόματος αρχείου (συμπεριλαμβανομένου του σημείου ".") π.χ. ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `extension` είναι None ή κενό. |

### Δείτε επίσης
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
