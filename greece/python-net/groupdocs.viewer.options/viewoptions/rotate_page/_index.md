---
title: "rotate_page μέθοδος"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Εφαρμόζει την δεξιόστροφη περιστροφή σε μια σελίδα."
type: docs
url: /el/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Εφαρμόζει την δεξιόστροφη περιστροφή σε μια σελίδα.

Για λεπτομέρειες, δείτε την τεκμηρίωση στο https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| page_number | `int` | Ο αριθμός σελίδας πρέπει να είναι αυστηρά μεγαλύτερος από 0. |
| rotation | `Rotation` | Η τιμή περιστροφής. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν η περιστροφή για τη σελίδα με αριθμό `page_number` είχε ήδη προστεθεί. |

### Δείτε επίσης
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
