---
title: "μέθοδος save_attachment"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αποθηκεύει το αρχείο συνημμένου στη ροή προορισμού."
type: docs
url: /el/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Αποθηκεύει το αρχείο συνημμένου στη ροή `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attachment | `Attachment` | Το συνημμένο. |
| destination | `io.RawIOBase` | Η εγγράψιμη ροή. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν `destination` είναι None. |
| `PasswordRequiredException` | Όταν απαιτείται κωδικός πρόσβασης για το άνοιγμα του εγγράφου. |
| `IncorrectPasswordException` | Όταν ο καθορισμένος κωδικός πρόσβασης είναι λανθασμένος. |
| `GroupDocsViewerException` | Όταν δεν βρέθηκε το συνημμένο. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Δείτε επίσης
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
