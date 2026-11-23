---
title: "μέθοδος get_view_info"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει προβολή και συγκεκριμένες πληροφορίες εγγράφου."
type: docs
url: /el/python-net/groupdocs.viewer/viewer/get_view_info/
is_root: false
weight: 1050
---


## get_view_info {#options}

Επιστρέφει προβολή και συγκεκριμένες πληροφορίες εγγράφου.

Μάθετε περισσότερα για το έγγραφο - τύπο αρχείου, αριθμό σελίδων και άλλες ιδιότητες συγκεκριμένες για τη μορφή:
- [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

```python
def get_view_info(self, options):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | `ViewInfoOptions` | Οι επιλογές πληροφοριών προβολής. |

**Returns:** Information about view and document specific information.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `options` είναι None. |
| `PasswordRequiredException` | Όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | Όταν ο καθορισμένος κωδικός πρόσβασης είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("document.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print(f"Pages: {len(info.pages)}")
    for page in info.pages:
        print(f"  Page {page.number}: {page.width}x{page.height}")
```

### Δείτε επίσης
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
