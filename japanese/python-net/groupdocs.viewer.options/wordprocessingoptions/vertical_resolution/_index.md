---
title: "vertical_resolution プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "生成された画像の垂直解像度（ドット毎インチ）。この解像度は、WordProcessing 文書を PNG または JPEG 形式にレンダリングする場合にのみ使用されます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/
is_root: false
weight: 2120
---


## vertical_resolution property

生成された画像の垂直解像度（ドット毎インチ）。この解像度は、WordProcessing 文書を PNG または JPEG 形式にレンダリングする場合にのみ使用されます。

既定値は 96 DPI です。

最小可能値は 72 DPI、最大可能値は 600 DPI です。ユーザーが指定した値がこれらの範囲外の場合、最も近い境界値が適用されます。

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
* class [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/)
