---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100."
type: docs
url: /fr/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100.

Pour plus de détails et des exemples de code, consultez https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ et ses sous‑pages.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Voir aussi
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
