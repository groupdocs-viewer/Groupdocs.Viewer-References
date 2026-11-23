---
title: "μέθοδος for_rendering_by_page_breaks"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία SpreadsheetOptions διαμορφωμένη για τη διαίρεση των φύλλων εργασίας σε σελίδες με βάση τα διαχωριστικά σελίδας."
type: docs
url: /el/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

Αρχικοποιεί ένα αντικείμενο [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) διαμορφωμένο ώστε να χωρίζει τα φύλλα εργασίας σε σελίδες με βάση τα διαχωριστικά σελίδας.

Για λεπτομέρειες, δείτε την τεκμηρίωση.

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # Φόρτωση λογιστικού φύλλου
    with Viewer("products.xlsx") as viewer:
        # Μετατροπή του λογιστικού φύλλου σε PDF.
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # Διαίρεση χρησιμοποιώντας διαχωριστικά σελίδας.
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### Δείτε επίσης
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
