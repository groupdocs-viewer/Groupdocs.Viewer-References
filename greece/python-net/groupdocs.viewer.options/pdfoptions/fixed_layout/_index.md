---
title: "ιδιότητα fixed_layout"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η επιλογή σταθερής διάταξης ενεργοποιεί την απόδοση εγγράφων PDF και EPUB σε HTML με σταθερή διάταξη."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

Η επιλογή σταθερής διάταξης ενεργοποιεί την απόδοση εγγράφων PDF και EPUB σε HTML με σταθερή διάταξη.

Τα έγγραφα PDF και EPUB αρχικά αποδίδονται σε HTML με σταθερή διάταξη για να διατηρηθεί η εμφάνιση του αρχικού εγγράφου. Αυτή η σταθερή διάταξη σημαίνει ότι όλα τα στοιχεία HTML έχουν ακριβείς θέσεις μέσα σε ένα κοντέινερ με καθορισμένο μέγεθος. Η αλλαγή μεγέθους του παραθύρου του προγράμματος περιήγησης δεν επηρεάζει τη θέση και το μέγεθος των στοιχείων στο έγγραφο.

Αυτή η επιλογή είναι διαθέσιμη μόνο κατά την απόδοση σε HTML. Η προεπιλεγμένη τιμή είναι `True`. Για απόδοση με ρευστή διάταξη, ορίστε αυτή την ιδιότητα σε `False`.

Κατά την απόδοση με ρευστή διάταξη, οι εικόνες παραλείπονται. Χρησιμοποιήστε ρευστή διάταξη όταν αποδίδετε έγγραφα PDF με κείμενο.

Για ένα παράδειγμα κώδικα, δείτε την τεκμηρίωση.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### Δείτε επίσης
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
