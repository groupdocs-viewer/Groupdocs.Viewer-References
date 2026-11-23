---
title: "método for_split_sheet_into_pages"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa una instancia de SpreadsheetOptions para renderizar una hoja en páginas."
type: docs
url: /es/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Inicializa una instancia de SpreadsheetOptions para renderizar una hoja en páginas.

Para obtener más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| count_rows_per_page | `int` | Cantidad de filas a incluir en cada página. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `count_rows_per_page` es igual o menor que cero. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Cargar hoja de cálculo
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Inicializa una instancia de SpreadsheetOptions para renderizar una hoja en páginas.

Para obtener más detalles, consulte la documentación en https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| count_rows_per_page | `int` | Cantidad de filas a incluir en cada página. |
| count_columns_per_page | `int` | Cantidad de columnas a incluir en cada página. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Lanza | Descripción |
| :- | :- |
| `ValueError` | Cuando `count_columns_per_page` es igual o menor que cero. |

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Cargar hoja de cálculo
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Convertir la hoja de cálculo a PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Dividir por número de filas y columnas.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### Ver también
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
