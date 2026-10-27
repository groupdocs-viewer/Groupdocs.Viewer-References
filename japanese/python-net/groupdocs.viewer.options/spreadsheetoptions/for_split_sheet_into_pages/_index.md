---
title: "for_split_sheet_into_pages メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "シートをページに分割してレンダリングするための SpreadsheetOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/
is_root: false
weight: 1050
---


## for_split_sheet_into_pages {#count_rows_per_page}

シートをページに分割してレンダリングするための SpreadsheetOptions インスタンスを初期化します。

詳細については、https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows のドキュメントをご覧ください。

```python
def for_split_sheet_into_pages(cls, count_rows_per_page):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| count_rows_per_page | `int` | 各ページに含める行数です。 |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering sheet into pages.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `count_rows_per_page` が 0 以下の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows():
    # スプレッドシートを読み込む
    with Viewer("two-pages.xlsx") as viewer:
        rows_per_page = 15
        view_options = PdfViewOptions("split_by_rows/by_rows.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(rows_per_page)
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows()
```

## for_split_sheet_into_pages {#count_rows_per_page-count_columns_per_page}

シートをページに分割してレンダリングするための SpreadsheetOptions インスタンスを初期化します。

詳細については、https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns のドキュメントをご覧ください。

```python
def for_split_sheet_into_pages(cls, count_rows_per_page, count_columns_per_page):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| count_rows_per_page | `int` | 各ページに含める行数です。 |
| count_columns_per_page | `int` | 各ページに含める列数です。 |

**Returns:** SpreadsheetOptions: New instance of the SpreadsheetOptions class for rendering a sheet into pages.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `count_columns_per_page` が 0 以下の場合。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_rows_and_columns():
    # スプレッドシートを読み込む
    with Viewer("four-pages.xlsx") as viewer:
        rows_per_page = 15
        columns_per_page = 7
        # スプレッドシートを PDF に変換します。
        view_options = PdfViewOptions("split_by_rows_and_columns/by_rows_and_columns.pdf")
        # 行数と列数で分割します。
        view_options.spreadsheet_options = SpreadsheetOptions.for_split_sheet_into_pages(
            rows_per_page, columns_per_page
        )
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_rows_and_columns()
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
