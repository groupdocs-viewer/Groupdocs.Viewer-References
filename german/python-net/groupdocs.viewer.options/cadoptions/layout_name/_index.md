---
title: "layout_name Eigenschaft"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Der Name des spezifischen Layouts, das gerendert werden soll."
type: docs
url: /de/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

Der Name des spezifischen Layouts, das gerendert werden soll. Der Layout-Name ist case-sensitive.

Diese Option ist nur für die CAD-Zeichnungen verfügbar, die Layouts unterstützen: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), und [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); Standardmäßig wird nur das Modell gerendert.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### Siehe auch
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
