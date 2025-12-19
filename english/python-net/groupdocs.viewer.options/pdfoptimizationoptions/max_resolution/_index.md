---
title: max_resolution property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/
is_root: false
weight: 70
---

## max_resolution property


Sets the maximum resolution in the output PDF file.

### Remarks 


To allow this option, set the [`PdfOptimizationOptions.compress_images`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions#compress_images) and [`PdfOptimizationOptions.max_resolution`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions#max_resolution) properties to `true`.




The default value is `300`.




For code example, see this [documentation](https://docs.groupdocs.com/viewer/net/optimization-pdf-set-max-resolution/).
### Definition:
```python
@property
def max_resolution(self):
    ...
@max_resolution.setter
def max_resolution(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions)
