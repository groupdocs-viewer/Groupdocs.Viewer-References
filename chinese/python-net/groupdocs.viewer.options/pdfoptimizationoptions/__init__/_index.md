---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "将 MaxResolution 选项的默认值初始化为 300，将 ImageQuality 选项的默认值初始化为 100。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

将 MaxResolution 选项的默认值初始化为 300，将 ImageQuality 选项的默认值初始化为 100。

有关详细信息和代码示例，请参阅 https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ 及其子页面。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### 另见
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
