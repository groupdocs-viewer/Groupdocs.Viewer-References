---
title: "page_size ιδιότητα"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Το μέγεθος της εξαγόμενης σελίδας."
type: docs
url: /el/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/
is_root: false
weight: 2060
---


## page_size property

Το μέγεθος της εξαγόμενης σελίδας.

Η προεπιλεγμένη τιμή είναι `PageSize.Unspecified`, που σημαίνει ότι χρησιμοποιείται ένα μέγεθος σελίδας που ορίζεται στις ρυθμίσεις σελίδας (Page Setup).

Κατά την απόδοση αρχείων HTM και HTML, το προεπιλεγμένο μέγεθος σελίδας ορίζεται σε Letter 792 x 612 σημεία.

Ως αποτέλεσμα, κάποιο περιεχόμενο μπορεί να μην χωράει στο πλαίσιο της σελίδας.

Ορίστε μεγαλύτερο μέγεθος σελίδας π.χ. `PageSize.A3` για να χωρέσει το περιεχόμενο.

### Definition:
```python
@property
def page_size(self):
    ...
@page_size.setter
def page_size(self, value):
    ...
```

### Δείτε επίσης
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
