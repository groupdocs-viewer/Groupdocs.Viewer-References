---
title: "Κλάση Attachment"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αντιπροσωπεύει ένα αρχείο συνημμένου που περιέχεται σε ένα μήνυμα email, αρχείο αρχειοθήκης, έγγραφο PDF ή αρχείο δεδομένων Outlook."
type: docs
url: /el/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Αντιπροσωπεύει ένα αρχείο συνημμένου που περιέχεται σε ένα μήνυμα email, αρχείο αρχειοθήκης, έγγραφο PDF ή αρχείο δεδομένων Outlook.

Ο τύπος Attachment εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Αρχικοποιεί μια νέα παρουσία του Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Αρχικοποιεί μια νέα παρουσία της κλάσης Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Αρχικοποιεί μια νέα παρουσία της κλάσης Attachment. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Το όνομα αρχείου του συνημμένου. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Η σχετική διαδρομή του συνημμένου, π.χ. `folder/file.docx`, ή το όνομα αρχείου όταν το αρχείο βρίσκεται στη ρίζα ενός αρχείου, σε ένα μήνυμα ηλεκτρονικού ταχυδρομείου ή σε ένα αρχείο δεδομένων. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Ο τύπος αρχείου του συνημμένου. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Το μοναδικό αναγνωριστικό του συνημμένου στο πλαίσιο ενός μοναδικού αρχείου που περιέχει αυτό το συνημμένο. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Το μέγεθος αρχείου του συνημμένου σε bytes. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Πρόσβαση στις ιδιότητες του συνημμένου, π.χ., όνομα αρχείου
        print(attachment.file_name)
        # Αποθήκευση του συνημμένου σε διαδρομή αρχείου
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
