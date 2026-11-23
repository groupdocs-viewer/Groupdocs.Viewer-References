---
title: "μέθοδος for_split_sheet_into_pages"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα αντικείμενο SpreadsheetOptions για την απόδοση ενός φύλλου σε σελίδες."
type: docs
url: /el/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Αρχικοποιεί ένα αντικείμενο SpreadsheetOptions για την απόδοση ενός φύλλου σε σελίδες.

Για λεπτομέρειες, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| count_rows_per_page | `int` | Αριθμός γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `count_rows_per_page` είναι ίσο ή μικρότερο από το μηδέν. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Φόρτωση λογιστικού φύλλου
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Αρχικοποιεί ένα αντικείμενο SpreadsheetOptions για την απόδοση ενός φύλλου σε σελίδες.

Για λεπτομέρειες, δείτε την τεκμηρίωση στη διεύθυνση https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| count_rows_per_page | `int` | Αριθμός γραμμών που θα συμπεριληφθούν σε κάθε σελίδα. |
| count_columns_per_page | `int` | Αριθμός στηλών που θα συμπεριληφθούν σε κάθε σελίδα. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν το `count_columns_per_page` είναι ίσο ή μικρότερο από το μηδέν. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Φόρτωση λογιστικού φύλλου
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Μετατροπή του λογιστικού φύλλου σε PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Διαίρεση ανά αριθμό γραμμών και στηλών.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Δείτε επίσης
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
