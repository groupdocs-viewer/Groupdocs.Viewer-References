---
title: for_split_sheet_into_pages method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a SpreadsheetOptions instance for rendering a sheet into pages."
type: docs
url: /python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Initializes a SpreadsheetOptions instance for rendering a sheet into pages.

For details, see the documentation.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| count_rows_per_page | `int` | Count of rows to include into each page. |

**Returns:** SpreadsheetOptions: New instance of SpreadsheetOptions for rendering sheet into pages.

| Raises | Description |
| :- | :- |
| `ValueError` | If `count_rows_per_page` is less than or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Initializes a SpreadsheetOptions instance for rendering a sheet into pages.

For details, see the documentation.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| count_rows_per_page | `int` | Count of rows to include into each page. |
| count_columns_per_page | `int` | Count of columns to include into each page. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Raises | Description |
| :- | :- |
| `ValueError` | When `count_columns_per_page` is less than or equal to zero. |

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

def split_by_rows_and_columns():
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)
```

### Aliases

These names call `for_split_sheet_into_pages` too, limited to the overloads listed.

| Alias | Accepts |
| :- | :- |
| `for_split_sheet_into_pages_int32` | `for_split_sheet_into_pages_int32(count_rows_per_page, count_columns_per_page)`<br>`for_split_sheet_into_pages_int32(count_rows_per_page)` |

### See Also
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
