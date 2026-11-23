---
title: "image_height プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力画像の高さ（ピクセル単位）。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/
is_root: false
weight: 2010
---


## image_height property

出力画像の高さ（ピクセル単位）。

このプロパティを使用して、出力画像の高さ（ピクセル単位）を設定します。GroupDocs.Viewer は単一画像を HTML にレンダリングする際にのみこのプロパティを適用します。詳細については、https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/ のドキュメントをご覧ください。

このプロパティを設定した場合、[`PdfViewOptions.ImageMaxHeight`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) プロパティは無視されます。

### Definition:
```python
@property
def image_height(self):
    ...
@image_height.setter
def image_height(self, value):
    ...
```

### 参照
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
