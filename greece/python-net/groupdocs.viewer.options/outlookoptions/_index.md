---
title: "OutlookOptions κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιέχει επιλογές για απόδοση αρχείων δεδομένων Outlook."
type: docs
url: /el/python-net/groupdocs.viewer.options/outlookoptions/
is_root: false
weight: 130
---


## OutlookOptions class

Περιέχει επιλογές για απόδοση αρχείων δεδομένων Outlook.

Για λεπτομέρειες, δείτε την τεκμηρίωση του GroupDocs.

Ο τύπος OutlookOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/outlookoptions/__init__/) |  |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [address_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/address_filter/) | Η διεύθυνση email που χρησιμοποιείται για φιλτράρισμα μηνυμάτων κατά αποστολέα ή παραλήπτη. |
| [folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/folder/) | Το όνομα του φακέλου (π.χ. Inbox, Sent Item ή Deleted Items) που θα αποδοθεί. |
| [max_items_in_folder](/viewer/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/) | Ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο. |
| [text_filter](/viewer/python-net/groupdocs.viewer.options/outlookoptions/text_filter/) | Οι λέξεις-κλειδιά που χρησιμοποιούνται για το φιλτράρισμα των μηνυμάτων. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_outlook():
    with Viewer("sample.pst") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "outlook.html"
        )
        # Περιορίστε τον αριθμό των στοιχείων που αποδίδονται ανά φάκελο.
        view_options.outlook_options.max_items_in_folder = 30
        viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
