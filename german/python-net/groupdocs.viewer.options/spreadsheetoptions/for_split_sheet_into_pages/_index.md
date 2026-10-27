---
title: "for_split_sheet_into_pages Methode"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine SpreadsheetOptions‑Instanz zum Rendern eines Blatts in Seiten."
type: docs
url: /de/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Initialisiert eine SpreadsheetOptions‑Instanz zum Rendern eines Blatts in Seiten.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| count_rows_per_page | `int` | Anzahl der Zeilen, die in jede Seite aufgenommen werden. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `count_rows_per_page` gleich null oder kleiner ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Tabellenblatt laden
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Initialisiert eine SpreadsheetOptions‑Instanz zum Rendern eines Blatts in Seiten.

Weitere Details finden Sie in der Dokumentation unter https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| count_rows_per_page | `int` | Anzahl der Zeilen, die in jede Seite aufgenommen werden. |
| count_columns_per_page | `int` | Anzahl der Spalten, die in jede Seite aufgenommen werden. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `count_columns_per_page` gleich null oder kleiner ist. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Tabellenblatt laden
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Konvertieren Sie das Tabellenblatt in PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Aufteilen nach Anzahl der Zeilen und Spalten.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Siehe auch
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
