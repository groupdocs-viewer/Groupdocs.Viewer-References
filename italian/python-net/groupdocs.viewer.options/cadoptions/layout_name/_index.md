---
title: "proprietà layout_name"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Il nome del layout specifico da renderizzare."
type: docs
url: /it/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

Il nome del layout specifico da renderizzare. Il nome del layout è sensibile al maiuscolo/minuscolo.

Questa opzione è disponibile solo per i disegni CAD che supportano i layout: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), e [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); Per impostazione predefinita viene renderizzato solo il Model.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### Vedi anche
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
