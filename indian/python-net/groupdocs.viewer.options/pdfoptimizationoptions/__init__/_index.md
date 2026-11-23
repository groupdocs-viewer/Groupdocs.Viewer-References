---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Viewer Python के लिए .NET के माध्यम से API संदर्भ"
description: "MaxResolution विकल्प के डिफ़ॉल्ट मान को 300 और ImageQuality विकल्प को 100 पर प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/
is_root: false
weight: 10
---


## __init__

MaxResolution विकल्प के डिफ़ॉल्ट मान को 300 और ImageQuality विकल्प को 100 पर प्रारंभ करता है।

विवरण और कोड नमूनों के लिए, https://docs.groupdocs.com/viewer/net/optimization-pdf-options/ और इसके उपपृष्ठ देखें।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

with Viewer("sample.docx") as viewer:
    view_options = PdfViewOptions("optimized.pdf")
    view_options.pdf_optimization_options = PdfOptimizationOptions()
    viewer.view(view_options)
```

### साथ में देखें
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
