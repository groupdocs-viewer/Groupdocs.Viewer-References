---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100."
type: docs
url: /de/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert die Standardwerte der Option MaxResolution auf 300 und der Option ImageQuality auf 100.

Für Details und Code‑Beispiele siehe https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ und die zugehörigen Seiten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Siehe auch
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
