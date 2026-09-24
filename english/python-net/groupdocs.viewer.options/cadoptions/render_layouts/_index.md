---
title: render_layouts property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The flag indicating whether layouts from the CAD document should be rendered."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

The flag indicating whether layouts from the CAD document should be rendered.

This option is available only for CAD drawings that support layouts [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), and [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). By default only the Model is rendered.

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
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
