---
title: "méthode for_split_sheet_into_pages"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une instance SpreadsheetOptions pour rendre une feuille en plusieurs pages."
type: docs
url: /fr/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Initialise une instance SpreadsheetOptions pour rendre une feuille en plusieurs pages.

Pour plus de détails, voir la documentation à https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| count_rows_per_page | `int` | Nombre de lignes à inclure dans chaque page. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `count_rows_per_page` est égal ou inférieur à zéro. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Charger la feuille de calcul
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Initialise une instance SpreadsheetOptions pour rendre une feuille en plusieurs pages.

Pour plus de détails, voir la documentation à https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| count_rows_per_page | `int` | Nombre de lignes à inclure dans chaque page. |
| count_columns_per_page | `int` | Nombre de colonnes à inclure dans chaque page. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `count_columns_per_page` est égal ou inférieur à zéro. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Charger la feuille de calcul
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Convertir la feuille de calcul en PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Diviser par nombre de lignes et de colonnes.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Voir aussi
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
