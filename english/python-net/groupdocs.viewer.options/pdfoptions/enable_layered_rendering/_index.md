---
title: enable_layered_rendering property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The property enables rendering text and graphics in the original PDF document's z-order when rendering to HTML."
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 2050
---


## enable_layered_rendering property

The property enables rendering text and graphics in the original PDF document's z-order when rendering to HTML.

By default, GroupDocs.Viewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is False.

For a code example, see the documentation.

### Definition:
```python
@property
def enable_layered_rendering(self):
    ...
@enable_layered_rendering.setter
def enable_layered_rendering(self, value):
    ...
```

### See Also
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
