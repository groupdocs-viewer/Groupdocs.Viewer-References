---
title: "tiles 属性"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "要渲染的绘图区域。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/cadoptions/tiles/
is_root: false
weight: 2090
---


## tiles property

要渲染的绘图区域。

此选项仅适用于 [`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/) 和 [`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/) 文件类型。当按瓦片渲染时，[`CadOptions.render_layouts`](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) 和 [`CadOptions.layout_name`](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) 选项将被忽略。

### Definition:
```python
@property
def tiles(self):
    ...
@tiles.setter
def tiles(self, value):
    ...
```

### 另见
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
