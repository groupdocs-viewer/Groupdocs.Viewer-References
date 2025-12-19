---
title: image_width property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/image_width/
is_root: false
weight: 110
---

## image_width property


Sets the width of an output image (in pixels).

### Remarks 


Use this property to set the output image width (in pixels).
GroupDocs.Viewer applies this property when rendering a single image to PDF.
For details, see the [documentation](https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).




If you set this property, the [`PdfViewOptions.image_max_width`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions#image_max_width) property is ignored.
### Definition:
```python
@property
def image_width(self):
    ...
@image_width.setter
def image_width(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)
