---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza i valori predefiniti dell'opzione MaxResolution a 300 e dell'opzione ImageQuality a 100."
type: docs
url: /it/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza i valori predefiniti dell'opzione MaxResolution a 300 e dell'opzione ImageQuality a 100.

Per dettagli e esempi di codice, vedere https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ e le relative pagine.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Vedi anche
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
