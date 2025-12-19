---
title: render_layouts property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 130
---

## render_layouts property


Flag if layouts from CAD document should be rendered.

### Remarks 


This option is available only for the CAD drawings that support layouts [`FileType.DXF`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.DWG`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.DWT`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.DWF`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.DWFX`](/viewer/python-net/groupdocs.viewer/filetype). 
By default only the Model is rendered.
### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
