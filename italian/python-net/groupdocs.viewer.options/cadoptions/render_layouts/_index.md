---
title: "proprietà render_layouts"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Il flag che indica se i layout del documento CAD devono essere renderizzati."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

Il flag che indica se i layout del documento CAD devono essere renderizzati.

Questa opzione è disponibile solo per i disegni CAD che supportano layout [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), e [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Per impostazione predefinita viene renderizzato solo il Model.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
