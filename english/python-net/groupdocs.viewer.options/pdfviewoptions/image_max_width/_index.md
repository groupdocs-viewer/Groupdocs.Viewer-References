---
title: image_max_width property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/
is_root: false
weight: 100
---

## image_max_width property


Sets the maximum width of an output image (in pixels).

### Remarks 


Use this property to set the maximum output image width (in pixels).
GroupDocs.Viewer applies this property when rendering a single image to PDF.
For details, see the [documentation](https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).




If you set the [`PdfViewOptions.image_width`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions#image_width) property, this property is ignored.
### Definition:
```python
@property
def image_max_width(self):
    ...
@image_max_width.setter
def image_max_width(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)
