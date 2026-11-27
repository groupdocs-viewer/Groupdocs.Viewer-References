---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of PdfOptimizationOptions with default MaxResolution of 300 and ImageQuality of 100."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of PdfOptimizationOptions with default MaxResolution of 300 and ImageQuality of 100.

For details and code samples, see the online documentation page.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.viewer.options import PdfOptimizationOptions

# Create options with default settings
pdf_opts = PdfOptimizationOptions()
# Enable removal of unused objects to reduce file size
pdf_opts.remove_unused_objects = True
```

### See Also
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
