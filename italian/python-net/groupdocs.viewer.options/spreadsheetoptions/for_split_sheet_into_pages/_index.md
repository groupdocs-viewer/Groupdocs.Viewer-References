---
title: "metodo for_split_sheet_into_pages"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza un'istanza di SpreadsheetOptions per il rendering di un foglio in pagine."
type: docs
url: /it/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Inizializza un'istanza di SpreadsheetOptions per il rendering di un foglio in pagine.

Per ulteriori dettagli, consulta la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| count_rows_per_page | `int` | Numero di righe da includere in ogni pagina. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `count_rows_per_page` è uguale o inferiore a zero. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Carica il foglio di calcolo
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Inizializza un'istanza di SpreadsheetOptions per il rendering di un foglio in pagine.

Per ulteriori dettagli, consulta la documentazione all'indirizzo https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| count_rows_per_page | `int` | Numero di righe da includere in ogni pagina. |
| count_columns_per_page | `int` | Numero di colonne da includere in ogni pagina. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Quando `count_columns_per_page` è uguale o inferiore a zero. |

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Carica il foglio di calcolo
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Converti il foglio di calcolo in PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Dividi per numero di righe e colonne.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Vedi anche
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
