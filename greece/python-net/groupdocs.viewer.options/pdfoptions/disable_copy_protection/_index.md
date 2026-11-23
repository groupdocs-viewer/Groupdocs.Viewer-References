---
title: "ιδιότητα disable_copy_protection"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

Η ιδιότητα απενεργοποιεί την προστασία αντιγραφής περιεχομένου κατά την απόδοση σε HTML.

Κατά την απόδοση αρχείων PDF με προστασία κατά της αντιγραφής κειμένου και εικόνων σε HTML, το GroupDocs.Viewer προσθέτει ένα χαρακτηριστικό `inert` HTML στην ετικέτα BODY του HTML. Η προεπιλεγμένη τιμή είναι `False`, που σημαίνει ότι το χαρακτηριστικό `inert` προστίθεται μόνο εάν το έγγραφο PDF είναι προστατευμένο.

Για ένα παράδειγμα κώδικα, δείτε την τεκμηρίωση.

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### Δείτε επίσης
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
