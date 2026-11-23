---
title: "метод for_split_sheet_into_pages"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр SpreadsheetOptions для рендеринга листа по страницам."
type: docs
url: /ru/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

Инициализирует экземпляр SpreadsheetOptions для рендеринга листа по страницам.

Для подробностей см. документацию по адресу https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| count_rows_per_page | `int` | Количество строк, включаемых в каждую страницу. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `count_rows_per_page` равен нулю или меньше. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # Загрузить таблицу
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

Инициализирует экземпляр SpreadsheetOptions для рендеринга листа по страницам.

Для подробностей см. документацию по адресу https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns.

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| count_rows_per_page | `int` | Количество строк, включаемых в каждую страницу. |
| count_columns_per_page | `int` | Количество столбцов, включаемых в каждую страницу. |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `count_columns_per_page` равен нулю или меньше. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # Загрузить таблицу
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # Конвертировать таблицу в PDF.
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # Разделить по количеству строк и столбцов.
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### См. также
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
