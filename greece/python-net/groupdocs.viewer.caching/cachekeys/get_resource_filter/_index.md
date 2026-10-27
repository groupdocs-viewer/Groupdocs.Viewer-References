---
title: "get_resource_filter μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει μια συμβολοσειρά φίλτρου για την αναζήτηση καταχωρήσεων cache που αντιπροσωπεύουν αντικείμενα Resource."
type: docs
url: /el/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Επιστρέφει μια συμβολοσειρά φίλτρου για την αναζήτηση καταχωρήσεων cache που αντιπροσωπεύουν αντικείμενα [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός της σελίδας. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `page_number` είναι μικρότερο ή ίσο με το μηδέν. |

### Δείτε επίσης
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
