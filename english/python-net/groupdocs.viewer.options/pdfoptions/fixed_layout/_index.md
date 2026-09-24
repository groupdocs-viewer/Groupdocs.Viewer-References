---
title: fixed_layout property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The fixed layout option enables rendering PDF and EPUB documents to HTML with a fixed layout."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

The fixed layout option enables rendering PDF and EPUB documents to HTML with a fixed layout.

PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window does not affect the position and size of elements in the document.

This option is only available when rendering to HTML. The default value is `True`. To render with a fluid layout, set this property to `False`.

When rendering to fluid layout, images are skipped. Use fluid layout when rendering PDF documents with text content.

For a code example, see the documentation.

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### See Also
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
