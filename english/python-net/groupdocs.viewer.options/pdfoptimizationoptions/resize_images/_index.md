---
title: resize_images property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/
is_root: false
weight: 130
---

## resize_images property


Enables setting the maximum resolution in the output PDF file.

### Remarks 


To allow this option, set the [`PdfOptimizationOptions.compress_images`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions#compress_images) property to `true`. This option allows setting the [`PdfOptimizationOptions.max_resolution`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions#max_resolution) property. For code example, see this [documentation](https://docs.groupdocs.com/viewer/net/optimization-pdf-set-max-resolution/).
### Definition:
```python
@property
def resize_images(self):
    ...
@resize_images.setter
def resize_images(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions)
