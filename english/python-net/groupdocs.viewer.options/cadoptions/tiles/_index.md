---
title: tiles property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/tiles/
is_root: false
weight: 150
---

## tiles property


The drawing regions to render.

### Remarks 


This option is available only for the [`FileType.DWG`](/viewer/python-net/groupdocs.viewer/filetype) and [`FileType.DWT`](/viewer/python-net/groupdocs.viewer/filetype) file types.
The [`CadOptions.render_layouts`](/viewer/python-net/groupdocs.viewer.options/cadoptions#render_layouts) and [`CadOptions.layout_name`](/viewer/python-net/groupdocs.viewer.options/cadoptions#layout_name) options are ignored when rendering by tiles.
### Definition:
```python
@property
def tiles(self):
    ...
@tiles.setter
def tiles(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
