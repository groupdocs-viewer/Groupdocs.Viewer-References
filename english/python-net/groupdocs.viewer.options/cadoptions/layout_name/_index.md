---
title: layout_name property
second_title: GroupDocs.Viewer for Python via .NET API References
description: "The name of the specific layout to render."
type: docs
url: /python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

The name of the specific layout to render. Layout name is case-sensitive.

This option is available only for the CAD drawings that support layouts: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), and [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); By default only the Model is rendered.

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
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
