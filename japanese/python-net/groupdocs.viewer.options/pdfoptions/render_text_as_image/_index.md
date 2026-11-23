---
title: "render_text_as_image プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このオプションは、PDF ファイル内のテキストを HTML 出力で画像としてレンダリングできるようにします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/
is_root: false
weight: 2090
---


## render_text_as_image property

このオプションは、PDF ファイル内のテキストを HTML 出力で画像としてレンダリングできるようにします。

このオプションが True に設定されている場合、GroupDocs.Viewer はテキストを HTML 出力で画像としてレンダリングします。これによりテキストは選択できず、文字のレンダリングが向上し、HTML で PDF のような外観が実現します。デフォルト値は False です。

このオプションは HTML へのレンダリングで利用可能です。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def render_text_as_image(self):
    ...
@render_text_as_image.setter
def render_text_as_image(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
