---
title: "свойство layout_name"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Имя конкретного макета для отображения."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

Имя конкретного макета для рендеринга. Имя макета чувствительно к регистру.

Эта опция доступна только для CAD‑чертежей, поддерживающих макеты: [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/), [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/), [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/), [`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/), и [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/); По умолчанию отображается только Model.

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### См. также
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
