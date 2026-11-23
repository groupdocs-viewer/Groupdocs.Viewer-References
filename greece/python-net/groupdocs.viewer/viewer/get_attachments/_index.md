---
title: "μέθοδος get_attachments"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο."
type: docs
url: /el/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Επιστρέφει τα συνημμένα που περιέχονται στο έγγραφο.

Μάθετε περισσότερα:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `PasswordRequiredException` | Εκτοξεύεται όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | Εκτοξεύεται όταν ο κωδικός πρόσβασης που καθορίστηκε είναι λανθασμένος. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Αποθηκεύστε κάθε συνημμένο σε ένα αρχείο
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Δείτε επίσης
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
