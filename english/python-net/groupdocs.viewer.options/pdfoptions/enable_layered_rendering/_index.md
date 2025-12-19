---
title: enable_layered_rendering property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/
is_root: false
weight: 70
---

## enable_layered_rendering property


Enables rendering text and graphics in the original PDF document's z-order when rendering to HTML.

### Remarks 


By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is `false`.




For code example, see the [documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enable-multi-layer-rendering).
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
* module [`groupdocs.viewer.options`](../../)
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions)
