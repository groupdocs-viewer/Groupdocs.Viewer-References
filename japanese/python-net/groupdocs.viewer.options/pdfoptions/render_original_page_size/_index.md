---
title: "render_original_page_size プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "出力ページサイズは、ソース PDF ドキュメントのページサイズに合わせて設定されます。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/
is_root: false
weight: 2080
---


## render_original_page_size property

出力ページサイズは、ソース PDF ドキュメントのページサイズに合わせて設定されます。

デフォルトでは、GroupDocs.Viewer はレンダリング品質向上のために出力画像のページサイズを計算します。このオプションを有効にすると、出力ページが元の PDF ドキュメントのページサイズ（ピクセル単位）と同じになることが保証されます。デフォルト値は False です。

このオプションは PNG または JPG 形式へのレンダリングで利用可能です。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def render_original_page_size(self):
    ...
@render_original_page_size.setter
def render_original_page_size(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
