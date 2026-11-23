---
title: "wrap_images_in_svg プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを可能にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/
is_root: false
weight: 2100
---


## wrap_images_in_svg property

このプロパティは、出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを可能にします。

デフォルトでは、PDF およびページレイアウトファイルを HTML にレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。レンダリングされた PNG 画像は出力 HTML 文書の背景として使用されます。

このオプションは、埋め込みリソースおよび外部リソースを使用して PDF およびページレイアウト形式のファイルを HTML にレンダリングする場合に利用可能です。出力 HTML 文書内の各画像を SVG タグでラップできるようにします。デフォルト値は False です。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def wrap_images_in_svg(self):
    ...
@wrap_images_in_svg.setter
def wrap_images_in_svg(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
