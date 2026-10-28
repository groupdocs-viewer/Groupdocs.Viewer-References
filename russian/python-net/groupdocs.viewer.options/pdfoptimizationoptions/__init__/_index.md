---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует значения по умолчанию параметра MaxResolution до 300 и параметра ImageQuality до 100."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует значения по умолчанию параметра MaxResolution до 300 и параметра ImageQuality до 100.

Для получения деталей и примеров кода см. https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ и его дочерние страницы.

```python
def __init__(self):
    ...
```

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### См. также
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
