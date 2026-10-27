---
title: "for_split_sheet_into_pages 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个 SpreadsheetOptions 实例，以将工作表渲染为多页。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

初始化一个 SpreadsheetOptions 实例，以将工作表渲染为多页。

有关详细信息，请参阅文档：https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows。

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| count_rows_per_page | `int` | 每页包含的行数。 |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `count_rows_per_page` 小于或等于零时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # 加载电子表格
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

初始化一个 SpreadsheetOptions 实例，以将工作表渲染为多页。

有关详细信息，请参阅文档：https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns。

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| count_rows_per_page | `int` | 每页包含的行数。 |
| count_columns_per_page | `int` | 每页包含的列数。 |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `count_columns_per_page` 小于或等于零时。 |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # 加载电子表格
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # 将电子表格转换为 PDF。
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # 按行数和列数拆分。
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### 另见
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
