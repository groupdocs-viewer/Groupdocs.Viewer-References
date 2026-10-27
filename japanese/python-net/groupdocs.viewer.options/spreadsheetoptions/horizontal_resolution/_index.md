---
title: "horizontal_resolution プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "生成された画像の水平解像度（ドット毎インチ）です。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/
is_root: false
weight: 2050
---


## horizontal_resolution property

生成された画像の水平解像度（dpi）。このオプションは、スプレッドシートを PNG または JPEG 形式でレンダリングする場合にのみ使用されます。

既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。ユーザー指定の値がこれらの範囲外の場合、最小または最大の可能な値が適用されます。

### Definition:
```python
@property
def horizontal_resolution(self):
    ...
@horizontal_resolution.setter
def horizontal_resolution(self, value):
    ...
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
