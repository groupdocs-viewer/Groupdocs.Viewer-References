---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "MaxResolution seçeneğinin varsayılan değerini 300'e ve ImageQuality seçeneğinin varsayılan değerini 100'e başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

MaxResolution seçeneğinin varsayılan değerini 300'e ve ImageQuality seçeneğinin varsayılan değerini 100'e başlatır.

Ayrıntılar ve kod örnekleri için, https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ ve alt sayfalara bakın.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Ayrıca Bakınız
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
