---
title: "ιδιότητα render_notes"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές."
type: docs
url: /el/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/
is_root: false
weight: 2130
---


## render_notes property

Η ιδιότητα ενεργοποιεί την απόδοση σημειώσεων και σχολίων για ορισμένες μορφές.

Ορισμένες μορφές, όπως παρουσιάσεις ή αρχεία Microsoft Project, μπορεί να περιέχουν σημειώσεις. Επίσης, τα αρχεία PDF μπορεί να έχουν αναδυόμενες σημειώσεις (συμβουλές-φυσαλίδες) που είναι κρυμμένες από προεπιλογή και είναι ορατές σε προβολέα PDF μόνο όταν τοποθετείται ο δείκτης του ποντικιού πάνω τους. Από προεπιλογή, το GroupDocs.Viewer δεν αποδίδει τέτοιες σημειώσεις και σημειώσεις (`False`). Για να το κάνετε αυτό, ορίστε αυτή την ιδιότητα σε `True`.

Για ένα παράδειγμα κώδικα, δείτε την τεκμηρίωση.

### Definition:
```python
@property
def render_notes(self):
    ...
@render_notes.setter
def render_notes(self, value):
    ...
```

### Δείτε επίσης
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
