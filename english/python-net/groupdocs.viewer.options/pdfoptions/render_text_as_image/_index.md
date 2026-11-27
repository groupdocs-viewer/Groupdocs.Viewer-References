---
title: render_text_as_image property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables rendering text in PDF files as an image in the HTML output."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2100
---


## render_text_as_image property

The property enables rendering text in PDF files as an image in the HTML output.

When set to `True`, GroupDocs.Viewer renders text as an image in the HTML output, making the text unselectable and enhancing character rendering to achieve a PDF‑like appearance. The default value is `False`.

This option is available only when rendering to HTML.

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
