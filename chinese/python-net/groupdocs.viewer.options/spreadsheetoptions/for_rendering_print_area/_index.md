---
title: "for_rendering_print_area 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 SpreadsheetOptions 类的实例，仅用于渲染打印区域。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/
is_root: false
weight: 1030
---


## for_rendering_print_area

初始化一个仅渲染打印区域的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 类实例。

有关详细信息，请参阅 https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-a-print-area 上的文档。

```python
def for_rendering_print_area(cls):
    ...
```

**Returns:** SpreadsheetOptions: New instance of the `SpreadsheetOptions` class for rendering print areas only.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area():
    with Viewer("invoice.xlsx") as viewer:
        view_options = PdfViewOptions("render_print_area/print_area.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area()
        viewer.view(view_options)
```

### 另见
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
