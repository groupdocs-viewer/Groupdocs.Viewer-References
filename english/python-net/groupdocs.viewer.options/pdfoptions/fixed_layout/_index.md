---
title: fixed_layout property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 90
---

## fixed_layout property


Enables rendering the PDF and EPUB documents to HTML with a fixed layout.

### Remarks 


PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document.    




This option is only available when rendering to HTML. The default value is `true`. To render with a fluid layout, set this property to `false`.




When rendering to fluid layout, images are skipped. Use fluid layout when rendering PDF documents with text content.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout).
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
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
