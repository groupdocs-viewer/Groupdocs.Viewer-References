---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert de standaardwaarden van de MaxResolution-optie op 300 en de ImageQuality-optie op 100."
type: docs
url: /nl/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert de standaardwaarden van de MaxResolution-optie op 300 en de ImageQuality-optie op 100.

Voor details en codevoorbeelden, zie https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ en de onderliggende pagina's.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Zie ook
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
