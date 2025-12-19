---
title: layout_name property
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 110
---

## layout_name property


The name of the specific layout to render. Layout name is case-sensitive.

### Remarks 


This option is available only for the CAD drawings that support layouts: [`FileType.DXF`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.DWG`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.DWT`](/viewer/python-net/groupdocs.viewer/filetype), [`FileType.DWF`](/viewer/python-net/groupdocs.viewer/filetype), and [`FileType.DWFX`](/viewer/python-net/groupdocs.viewer/filetype);
By default only the Model is rendered.
### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### See Also
* module [`groupdocs.viewer.options`](../../)
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions)
