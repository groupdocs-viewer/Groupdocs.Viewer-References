---
title: wrap_images_in_svg property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 130
---

## wrap_images_in_svg property


Enables wrapping each image in the output HTML document in SVG tag to improve the output quality.

### Remarks 


By default, when rendering PDF and Page Layout files to HTML, all images are rendered as one PNG image.
The rendered PNG image is used as the background for the output HTML document.




This option is available when rendering [PDF and Page Layout file formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) to HTML with embedded and external resources. It enables wrapping each image in the output HTML document in SVG tag. The default value is `false`.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).
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
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
