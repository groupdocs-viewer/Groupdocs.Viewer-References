---
title: "for_rendering_print_area_and_page_breaks 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 SpreadsheetOptions 类的实例，用于渲染打印区域和分页符。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/
is_root: false
weight: 1040
---


## for_rendering_print_area_and_page_breaks

初始化一个用于渲染打印区域和分页符的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 类实例。

有关详细信息，请参阅位于 https://docs.groupdocs.com/viewer/net/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area 的文档。

```python
def for_rendering_print_area_and_page_breaks(cls):
    ...
```

**Returns:** New instance of the `SpreadsheetOptions` class for rendering pages based on page breaks that are included into the print area. The behavior is similar to printing in Excel.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def render_print_area_and_page_breaks():
    with Viewer("products.xlsx") as viewer:
        view_options = PdfViewOptions("print_area_and_page_breaks.pdf")
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_print_area_and_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    render_print_area_and_page_breaks()
```

### 另见
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
