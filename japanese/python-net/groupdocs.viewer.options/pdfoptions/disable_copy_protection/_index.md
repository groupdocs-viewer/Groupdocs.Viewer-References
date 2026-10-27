---
title: "disable_copy_protection プロパティ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "このプロパティは、HTML へのレンダリング時にコンテンツのコピー保護を無効にします。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/
is_root: false
weight: 2020
---


## disable_copy_protection property

このプロパティは、HTML へのレンダリング時にコンテンツのコピー保護を無効にします。

テキストや画像のコピーから保護された PDF ファイルを HTML にレンダリングする際、GroupDocs.Viewer は HTML の BODY タグに `inert` 属性を追加します。デフォルト値は `False` で、PDF 文書が保護されている場合にのみ `inert` 属性が追加されることを意味します。

コード例については、ドキュメントをご覧ください。

### Definition:
```python
@property
def disable_copy_protection(self):
    ...
@disable_copy_protection.setter
def disable_copy_protection(self, value):
    ...
```

### 参照
* class [`PdfOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptions/)
