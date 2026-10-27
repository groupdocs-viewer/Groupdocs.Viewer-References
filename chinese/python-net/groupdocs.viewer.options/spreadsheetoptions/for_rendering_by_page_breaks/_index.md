---
title: "for_rendering_by_page_breaks 方法"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化一个配置为按分页符将工作表拆分为页面的 SpreadsheetOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/
is_root: false
weight: 1020
---


## for_rendering_by_page_breaks

初始化一个已配置为按分页符将工作表拆分为多页的 [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) 实例。

有关详细信息，请参阅文档。

```python
def for_rendering_by_page_breaks(cls):
    ...
```

**Returns:** New `SpreadsheetOptions` instance for splitting to pages by page breaks. The behavior is similar to printing in Excel.

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, SpreadsheetOptions

def split_by_page_breaks():
    # 加载电子表格
    with Viewer("products.xlsx") as viewer:
        # 将电子表格转换为 PDF。
        view_options = PdfViewOptions("split_by_page_breaks/by_page_breaks.pdf")
        # 使用分页符进行拆分。
        view_options.spreadsheet_options = SpreadsheetOptions.for_rendering_by_page_breaks()
        viewer.view(view_options)

if __name__ == "__main__":
    split_by_page_breaks()
```

### 另见
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
