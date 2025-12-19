---
title: render_original_page_size property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 110
---

## render_original_page_size property


Sets the output page size the same as the source PDF document's page size.

### Remarks 


By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is `false`.




This option is available for rendering to PNG or JPG formats.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#preserve-the-size-of-document-pages).
### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
