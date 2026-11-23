---
title: "ιδιότητα max_items_in_folder"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο."
type: docs
url: /el/python-net/groupdocs.viewer.options/outlookoptions/max_items_in_folder/
is_root: false
weight: 2030
---


## max_items_in_folder property

Ο μέγιστος αριθμός μηνυμάτων ή στοιχείων που μπορούν να αποδοθούν από έναν φάκελο.

Τα αρχεία δεδομένων Outlook μπορεί να είναι μεγάλα και η ανάκτηση όλων των μηνυμάτων μπορεί να διαρκέσει σημαντικό χρόνο. Αυτή η ιδιότητα περιορίζει τον μέγιστο αριθμό μηνυμάτων ή στοιχείων που αποδίδονται. Η προεπιλεγμένη τιμή είναι `50`. Για να αποδώσετε όλα τα μηνύματα, ορίστε την τιμή σε `0`.

Για ένα παράδειγμα κώδικα, δείτε την τεκμηρίωση.

### Definition:
```python
@property
def max_items_in_folder(self):
    ...
@max_items_in_folder.setter
def max_items_in_folder(self, value):
    ...
```

### Δείτε επίσης
* class [`OutlookOptions`](/viewer/python-net/groupdocs.viewer.options/outlookoptions/)
