---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar standardvärden för MaxResolution-alternativet till 300 och ImageQuality-alternativet till 100."
type: docs
url: /sv/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar standardvärden för MaxResolution-alternativet till 300 och ImageQuality-alternativet till 100.

För detaljer och kodexempel, se https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ och dess underliggande sidor.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Se även
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
