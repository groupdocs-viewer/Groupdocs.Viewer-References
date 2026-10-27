---
title: "vertical_resolution プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "生成された画像の垂直解像度（dpi）です。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/
is_root: false
weight: 2160
---


## vertical_resolution property

生成された画像の垂直解像度（dpi）です。このオプションはスプレッドシートを PNG または JPEG 形式に描画する場合にのみ使用されます。

デフォルト値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。ユーザー指定の値がこれらの範囲外の場合、最も近い境界値が適用されます。

### Definition:
```python
@property
def vertical_resolution(self):
    ...
@vertical_resolution.setter
def vertical_resolution(self, value):
    ...
```

### 参照
* class [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/)
