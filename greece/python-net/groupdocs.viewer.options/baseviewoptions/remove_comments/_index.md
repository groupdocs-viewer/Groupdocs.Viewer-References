---
title: "ιδιότητα remove_comments"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα απενεργοποιεί την απόδοση σχολίων όταν οριστεί σε True."
type: docs
url: /el/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/
is_root: false
weight: 2100
---


## remove_comments property

Η ιδιότητα απενεργοποιεί την απόδοση σχολίων όταν ορίζεται σε True. Από προεπιλογή είναι False, έτσι όλα τα σχόλια εμφανίζονται.

Ορισμένες μορφές εγγράφων όπως PDF και WordProcessing μπορεί να περιέχουν σχόλια. Από προεπιλογή το GroupDocs.Viewer τα αποδίδει. Με αυτή την επιλογή ορισμένη σε True, τα σχόλια μπορεί να εξαιρεθούν από το τελικό έγγραφο.

Αυτή η επιλογή αντικαθιστά την παρωχημένη ιδιότητα `RenderComments`.

### Definition:
```python
@property
def remove_comments(self):
    ...
@remove_comments.setter
def remove_comments(self, value):
    ...
```

### Δείτε επίσης
* class [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)
