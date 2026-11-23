---
title: "propiedad render_layouts"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "La bandera que indica si se deben renderizar los diseños del documento CAD."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

La bandera que indica si se deben renderizar los diseños del documento CAD.

Esta opción está disponible solo para dibujos CAD que admiten diseños [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), y [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Por defecto solo se renderiza el Modelo.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Ver también
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
