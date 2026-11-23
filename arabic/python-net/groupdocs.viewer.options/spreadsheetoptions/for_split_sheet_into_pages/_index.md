---
title: "طريقة for_split_sheet_into_pages"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ مثالًا من SpreadsheetOptions لتصوير ورقة إلى صفحات."
type: docs
url: /ar/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

يُهيئ مثالًا من SpreadsheetOptions لتصوير ورقة إلى صفحات.

للتفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| count_rows_per_page | `int` | عدد الصفوف التي سيتم تضمينها في كل صفحة. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `count_rows_per_page` مساوية للصفر أو أقل. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # تحميل جدول البيانات
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

يُهيئ مثالًا من SpreadsheetOptions لتصوير ورقة إلى صفحات.

للتفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| count_rows_per_page | `int` | عدد الصفوف التي سيتم تضمينها في كل صفحة. |
| count_columns_per_page | `int` | عدد الأعمدة التي سيتم تضمينها في كل صفحة. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | عندما تكون `count_columns_per_page` مساوية للصفر أو أقل. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # تحميل جدول البيانات
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # تحويل جدول البيانات إلى PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # تقسيم حسب عدد الصفوف والأعمدة.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### انظر أيضًا
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
