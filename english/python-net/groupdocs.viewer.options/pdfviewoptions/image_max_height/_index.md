---
title: image_max_height property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/
is_root: false
weight: 90
---

## image_max_height property


Sets the maximum height of an output image (in pixels).

### Remarks 


Use this property to set the maximum output image height (in pixels).
GroupDocs.Viewer applies this property when rendering a single image to PDF.
For details, see the [documentation](https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).




If you set the [`PdfViewOptions.image_height`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions#image_height) property, this property is ignored.
### Definition:
```python
@property
def image_max_height(self):
    ...
@image_max_height.setter
def image_max_height(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions)
