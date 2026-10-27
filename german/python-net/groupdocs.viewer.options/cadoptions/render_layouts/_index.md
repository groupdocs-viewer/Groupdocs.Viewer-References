---
title: "render_layouts Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Das Flag, das angibt, ob Layouts aus dem CAD-Dokument gerendert werden sollen."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

Das Flag, das angibt, ob Layouts aus dem CAD-Dokument gerendert werden sollen.

Diese Option ist nur für CAD-Zeichnungen verfügbar, die Layouts unterstützen [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), und [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Standardmäßig wird nur das Modell gerendert.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Siehe auch
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
