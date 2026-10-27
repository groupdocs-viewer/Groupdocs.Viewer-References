---
title: "get_resource_key μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αντικείμενο Resource."
type: docs
url: /el/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Επιστρέφει μοναδικό αναγνωριστικό για την καταχώρηση cache που αντιπροσωπεύει το αντικείμενο [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός της σελίδας. |
| resource | `Resource` | Ο πόρος HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `page_number` είναι μικρότερο ή ίσο με το μηδέν, ή εάν το `resource` είναι None. |

### Δείτε επίσης
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
