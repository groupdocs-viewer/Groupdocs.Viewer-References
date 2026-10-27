---
title: "for_rendering_by_page_breaks メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ページ区切りでワークシートをページに分割するように設定された SpreadsheetOptions インスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

ページ区切りでワークシートをページに分割するように構成された [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) インスタンスを初期化します。

詳細については、ドキュメントをご覧ください。

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # スプレッドシートを読み込む
    with Viewer("products.xlsx") as viewer:
        # スプレッドシートを PDF に変換します。
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # ページ区切りを使用して分割します。
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
