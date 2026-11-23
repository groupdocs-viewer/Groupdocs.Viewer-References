---
title: "Κλάση Security"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Οι επιλογές ασφαλείας εγγράφου PDF."
type: docs
url: /el/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Οι επιλογές ασφαλείας εγγράφου PDF.

Για λεπτομέρειες, δείτε την τεκμηρίωση.

Ο τύπος Security εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Αρχικοποιεί μια παρουσία της κλάσης [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Ο κωδικός πρόσβασης που απαιτείται για το άνοιγμα του εγγράφου PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Τα δικαιώματα του εγγράφου PDF όπως εκτύπωση, τροποποίηση και εξαγωγή δεδομένων. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Ο κωδικός πρόσβασης που απαιτείται για την αλλαγή των ρυθμίσεων δικαιωμάτων. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
Οδηγοί εργασιών που χρησιμοποιούν `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
