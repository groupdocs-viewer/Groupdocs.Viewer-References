---
title: wrap_images_in_svg property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property that enables wrapping each image in the output HTML document in an SVG tag to improve output quality."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

The property that enables wrapping each image in the output HTML document in an SVG tag to improve output quality.

By default, when rendering PDF and Page Layout files to HTML, all images are rendered as one PNG image. The rendered PNG image is used as the background for the output HTML document.

This option is available when rendering PDF and Page Layout file formats to HTML with embedded and external resources. It enables wrapping each image in the output HTML document in an SVG tag. The default value is False.

For a code example, see the documentation.

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### See Also
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
