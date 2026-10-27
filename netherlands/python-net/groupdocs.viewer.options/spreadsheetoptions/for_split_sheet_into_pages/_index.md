---
title: "for_split_sheet_into_pages methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een SpreadsheetOptions‑instantie voor het renderen van een blad in pagina's."
type: docs
url: /nl/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Initialiseert een SpreadsheetOptions‑instantie voor het renderen van een blad in pagina's.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| count_rows_per_page | `int` | Aantal rijen om in elke pagina op te nemen. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `count_rows_per_page` gelijk is aan of kleiner dan nul. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Laad spreadsheet
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Initialiseert een SpreadsheetOptions‑instantie voor het renderen van een blad in pagina's.

Voor details, zie de documentatie op https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| count_rows_per_page | `int` | Aantal rijen om in elke pagina op te nemen. |
| count_columns_per_page | `int` | Aantal kolommen om in elke pagina op te nemen. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `count_columns_per_page` gelijk is aan of kleiner dan nul. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Laad spreadsheet
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Converteer de spreadsheet naar PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Splits op basis van aantal rijen en kolommen.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Zie ook
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
