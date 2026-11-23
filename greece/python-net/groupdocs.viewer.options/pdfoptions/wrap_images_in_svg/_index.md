---
title: "ιδιότητα wrap_images_in_svg"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα που ενεργοποιεί την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG για βελτίωση της ποιότητας εξόδου."
type: docs
url: /el/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

Η ιδιότητα που ενεργοποιεί την περιτύλιξη κάθε εικόνας στο έγγραφο HTML εξόδου με ετικέτα SVG για βελτίωση της ποιότητας εξόδου.

Από προεπιλογή, όταν αποδίδονται αρχεία PDF και Page Layout σε HTML, όλες οι εικόνες αποδίδονται ως μία εικόνα PNG. Η αποδοθείσα εικόνα PNG χρησιμοποιείται ως φόντο για το τελικό έγγραφο HTML.

Αυτή η επιλογή είναι διαθέσιμη όταν αποδίδονται μορφές αρχείων PDF και Page Layout σε HTML με ενσωματωμένους και εξωτερικούς πόρους. Επιτρέπει την περιτύλιξη κάθε εικόνας στο τελικό έγγραφο HTML σε ετικέτα SVG. Η προεπιλεγμένη τιμή είναι False.

Για ένα παράδειγμα κώδικα, δείτε την τεκμηρίωση.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### Δείτε επίσης
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
