---
title: render_text_as_image property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 120
---

## render_text_as_image property


Enables rendering texts in the PDF files as an image in the HTML output.

### Remarks 


When this option is set to `true`, GroupDocs.Viewer renders text as an image in the HTML output. This makes the text unselectable and enhances character rendering, ensuring a PDF-like appearance in HTML. The default value is `false`.




This option is available for  rendering to HTML.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#render-text-as-an-image).
### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
