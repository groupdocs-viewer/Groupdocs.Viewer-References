---
title: render_original_page_size property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The output page size is set to match the source PDF document's page size."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

The output page size is set to match the source PDF document's page size.

By default, GroupDocs.Viewer calculates the output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is False.

This option is available for rendering to PNG or JPG formats.

For a code example, see the documentation.

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
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
