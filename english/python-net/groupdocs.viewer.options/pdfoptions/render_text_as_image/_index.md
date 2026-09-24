---
title: render_text_as_image property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The option enables rendering texts in PDF files as an image in the HTML output."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

The option enables rendering texts in PDF files as an image in the HTML output.

When this option is set to True, GroupDocs.Viewer renders text as an image in the HTML output. This makes the text unselectable and enhances character rendering, ensuring a PDF‑like appearance in HTML. The default value is False.

This option is available for rendering to HTML.

For code example, see the documentation.

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
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
