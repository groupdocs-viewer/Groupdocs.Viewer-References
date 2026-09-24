---
title: image_height property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The height of an output image in pixels."
type: docs
url: /python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

The height of an output image in pixels.

Use this property to set the output image height (in pixels). GroupDocs.Viewer applies this property when rendering a single image to HTML only. For details, see the documentation at https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/.

If you set this property, the [`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) property is ignored.

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### See Also
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
