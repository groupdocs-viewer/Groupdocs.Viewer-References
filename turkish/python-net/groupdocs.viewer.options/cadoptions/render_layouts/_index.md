---
title: "render_layouts özelliği"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "CAD belgesindeki yerleşimlerin render edilip edilmeyeceğini belirten bayrak."
type: docs
url: /tr/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

CAD belgesindeki yerleşimlerin render edilip edilmeyeceğini belirten bayrak.

Bu seçenek yalnızca düzenleri destekleyen CAD çizimleri için kullanılabilir [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), ve [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). Varsayılan olarak yalnızca Model render edilir.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### Ayrıca Bakınız
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
