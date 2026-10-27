---
title: "get_attachment_key μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο συνημμένου."
type: docs
url: /el/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αρχείο συνημμένου.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attachment_id | `str` | Μοναδικό (στο πλαίσιο ενός μόνο αρχείου) αναγνωριστικό του συνημμένου. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εκτοπίζεται όταν το `attachment_id` είναι null ή κενό. |

### Δείτε επίσης
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
