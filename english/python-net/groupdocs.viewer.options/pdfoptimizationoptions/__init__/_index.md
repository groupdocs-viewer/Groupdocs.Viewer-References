---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes default values of MaxResolution option to 300 and ImageQuality option to 100."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes default values of MaxResolution option to 300 and ImageQuality option to 100.

For details and code samples, see https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ and its children.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### See Also
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
