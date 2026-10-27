---
title: "for_one_page_per_sheet メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "シート全体を 1 ページにレンダリングするための SpreadsheetOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/
is_root: false
weight: 1010
---


## for_one_page_per_sheet

全シートを 1 ページにレンダリングするための [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) インスタンスを初期化します。

詳細については、ドキュメントをご覧ください。

```python
def for_one_page_per_sheet(cls):
    ...
```

**Returns:** `SpreadsheetOptions`: A new instance configured to render the whole sheet into one page.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_one_page_per_sheet():
    # スプレッドシートを読み込む
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("render_one_page_per_sheet/one_page_per_sheet.pdf")
        # 各ワークシートを 1 ページにレンダリングします。
        view_options.spreadsheet_options = SpreadsheetOptions.for_one_page_per_sheet()
        viewer.view(view_options)

if __name__ == "__main__":
    render_one_page_per_sheet()
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
