---
title: "propiedad layout_name"
second_title: "Referencias de API de GroupDocs.Viewer para Python vía .NET"
description: "El nombre del diseño específico a renderizar."
type: docs
url: /es/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

El nombre del diseño específico a renderizar. El nombre del diseño distingue entre mayúsculas y minúsculas.

Esta opción está disponible solo para los dibujos CAD que admiten diseños: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), y [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); por defecto solo se renderiza el Modelo.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### Ver también
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
