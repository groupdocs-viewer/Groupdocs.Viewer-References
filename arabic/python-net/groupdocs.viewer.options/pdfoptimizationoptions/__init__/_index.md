---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يُهيئ القيم الافتراضية للخيار MaxResolution إلى 300 والخيار ImageQuality إلى 100."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

يُهيئ القيم الافتراضية للخيار MaxResolution إلى 300 والخيار ImageQuality إلى 100.

للتفاصيل وعينات الشيفرة، راجع https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ وأقسامه الفرعية.

```python
def __init__(self):
    ...
```

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### انظر أيضًا
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
