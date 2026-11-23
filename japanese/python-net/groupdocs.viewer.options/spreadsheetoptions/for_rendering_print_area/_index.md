---
title: "for_rendering_print_area メソッド"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "印刷領域のみをレンダリングするための SpreadsheetOptions クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

印刷領域のみをレンダリングするための [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) クラスのインスタンスを初期化します。

詳細については、https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area のドキュメントをご参照ください。

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
