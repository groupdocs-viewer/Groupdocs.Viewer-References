---
title: "render_layouts プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "CAD ドキュメントからのレイアウトをレンダリングするかどうかを示すフラグです。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/render_layouts/
is_root: false
weight: 2070
---


## render_layouts property

CAD ドキュメントからのレイアウトをレンダリングするかどうかを示すフラグです。

このオプションは、レイアウトをサポートする CAD 図面（[`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/)、[`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/)、[`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/)、[`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/)、[`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/)）にのみ利用可能です。デフォルトではモデルのみがレンダリングされます。

### Definition:
```python
@property
def render_layouts(self):
    ...
@render_layouts.setter
def render_layouts(self, value):
    ...
```

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
