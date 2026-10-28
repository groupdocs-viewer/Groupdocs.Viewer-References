---
title: "свойство render_layouts"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Флаг, указывающий, следует ли рендерить макеты из документа CAD."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

Флаг, указывающий, следует ли рендерить макеты из документа CAD.

Эта опция доступна только для чертежей CAD, поддерживающих макеты [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), и [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/). По умолчанию рендерится только Model.

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### См. также
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
