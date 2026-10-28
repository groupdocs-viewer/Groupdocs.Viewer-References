---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "Inicializa los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100."
type: docs
url: /es/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa los valores predeterminados de la opción MaxResolution a 300 y de la opción ImageQuality a 100.

Para obtener detalles y ejemplos de código, consulte https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ y sus secciones.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### Ver también
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
