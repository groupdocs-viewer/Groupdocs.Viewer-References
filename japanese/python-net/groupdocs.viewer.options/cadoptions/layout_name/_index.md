---
title: "layout_name プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "レンダリングする特定のレイアウトの名前です。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/layout_name/
is_root: false
weight: 2050
---


## layout_name property

レンダリングする特定のレイアウト名です。レイアウト名は大文字小文字を区別します。

このオプションは、レイアウトをサポートする CAD 図面（[`FileType.dxf`](/viewer/python-net/groupdocs.viewer/filetype/dxf/)、[`FileType.dwg`](/viewer/python-net/groupdocs.viewer/filetype/dwg/)、[`FileType.dwt`](/viewer/python-net/groupdocs.viewer/filetype/dwt/)、[`FileType.dwf`](/viewer/python-net/groupdocs.viewer/filetype/dwf/)、[`FileType.dwfx`](/viewer/python-net/groupdocs.viewer/filetype/dwfx/)）でのみ利用可能です。デフォルトでは Model のみがレンダリングされます。

### Definition:
```python
@property
def layout_name(self):
    ...
@layout_name.setter
def layout_name(self, value):
    ...
```

### 参照
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
