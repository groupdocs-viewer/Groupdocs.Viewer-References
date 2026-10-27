---
title: "layout_name 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "要渲染的特定布局的名称。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

要渲染的特定布局名称。布局名称区分大小写。

此选项仅适用于支持布局的 CAD 图纸：[`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/)、[`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/)、[`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/)、[`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/)、以及 [`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/)；默认情况下仅渲染模型。

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
