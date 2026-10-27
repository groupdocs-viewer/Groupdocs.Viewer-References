---
title: "ιδιότητα try_repair"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Η ιδιότητα επιτρέπει στο GroupDocs.Viewer να προσπαθήσει την επισκευή δομικής διαφθοράς σε έγγραφα PDF."
type: docs
url: /el/python-net/groupdocs.viewer.options/loadoptions/try_repair/
is_root: false
weight: 2070
---


## try_repair property

Η ιδιότητα επιτρέπει στο GroupDocs.Viewer να προσπαθήσει να επισκευάσει τη δομική αλλοίωση σε έγγραφα PDF. Η προεπιλογή είναι False.

Αυτή η λειτουργία αντιμετωπίζει τα ακόλουθα ζητήματα σε ένα έγγραφο PDF:

- Broken references within the document (incorrect object offsets in the Cross-reference list).
- Missing critical elements like root object, page object, or page content.
- Circular references (Form X-object referencing itself).

### Definition:
```python
@property
def try_repair(self):
    ...
@try_repair.setter
def try_repair(self, value):
    ...
```

### Δείτε επίσης
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
