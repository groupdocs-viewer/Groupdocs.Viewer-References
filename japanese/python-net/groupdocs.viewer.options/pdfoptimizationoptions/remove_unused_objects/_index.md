---
title: "remove_unused_objects プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、PDF ファイルから未使用（孤立）オブジェクトを削除します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/
is_root: false
weight: 2090
---


## remove_unused_objects property

このプロパティは、PDF ファイルから未使用（孤立）オブジェクトを削除します。

これらのオブジェクトは PDF ドキュメントに配置されていますが、任意のページのリソース辞書から参照されておらず、全く使用されていません。このプロパティを有効にすると (`True`)、出力 PDF ドキュメントのサイズが縮小します。デフォルトでは無効 (`False`) です。

### Definition:
```python
@property
def remove_unused_objects(self):
    ...
@remove_unused_objects.setter
def remove_unused_objects(self, value):
    ...
```

### 参照
* class [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/)
