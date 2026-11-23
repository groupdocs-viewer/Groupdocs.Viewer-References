---
title: "fixed_layout プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "固定レイアウトオプションは、PDF および EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを可能にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/
is_root: false
weight: 2060
---


## fixed_layout property

固定レイアウトオプションは、PDF および EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを可能にします。

PDF および EPUB ドキュメントは、元のドキュメントの外観を維持するために、最初に固定レイアウトで HTML にレンダリングされます。この固定レイアウトでは、すべての HTML 要素が設定されたサイズのコンテナ内で正確な位置に配置されます。ブラウザウィンドウのサイズ変更は、ドキュメント内の要素の位置やサイズに影響しません。

このオプションは HTML へのレンダリング時にのみ利用可能です。デフォルト値は `True` です。流動的なレイアウトでレンダリングするには、このプロパティを `False` に設定してください。

流動的なレイアウトでレンダリングする場合、画像はスキップされます。テキストコンテンツのみの PDF ドキュメントをレンダリングする際に流動的なレイアウトを使用してください。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def fixed_layout(self):
    ...
@fixed_layout.setter
def fixed_layout(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
