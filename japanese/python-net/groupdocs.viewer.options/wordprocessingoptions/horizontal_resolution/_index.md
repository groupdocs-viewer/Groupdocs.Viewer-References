---
title: "horizontal_resolution プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "生成された画像の水平解像度（ドット毎インチ）です。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/
is_root: false
weight: 2030
---


## horizontal_resolution property

生成された画像の水平解像度（ドット毎インチ）。このオプションは、WordProcessing 文書を PNG または JPEG 形式にレンダリングする場合にのみ使用されます。

既定値は 96 DPI です。最小可能値は 72 DPI、最大可能値は 600 DPI です。ユーザーが指定した値がこれらの範囲外の場合、最も近い境界値（最小または最大）が適用されます。

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
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
