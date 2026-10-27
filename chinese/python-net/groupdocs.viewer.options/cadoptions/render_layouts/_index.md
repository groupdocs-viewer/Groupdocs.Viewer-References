---
title: "render_layouts 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "指示是否应渲染 CAD 文档中布局的标志。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

指示是否应渲染 CAD 文档中布局的标志。

此选项仅适用于支持布局的 CAD 图纸，布局包括 [`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/)、[`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/)、[`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/)、[`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/) 和 [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/)。默认情况下仅渲染模型。

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
