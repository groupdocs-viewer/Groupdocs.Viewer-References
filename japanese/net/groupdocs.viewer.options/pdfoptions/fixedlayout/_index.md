---
title: "FixedLayout"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PDF と EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを有効にします。"
type: docs
weight: 70
url: /ja/net/groupdocs.viewer.options/pdfoptions/fixedlayout/
---

## PdfOptions.FixedLayout property

PDF と EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを有効にします。

```csharp
public bool FixedLayout { get; set; }
```

### 備考

PDF と EPUB の文書は、最初に固定レイアウトで HTML にレンダリングされ、元の文書の外観を維持します。この固定レイアウトにより、すべての HTML 要素は設定されたサイズのコンテナ内で正確な位置に配置されます。ブラウザウィンドウのサイズ変更は、文書内の要素の位置やサイズに影響しません。

このオプションは HTML へのレンダリング時のみ利用可能です。デフォルト値は `true` です。流動レイアウトでレンダリングするには、このプロパティを `false` に設定してください。

流動レイアウトでレンダリングする場合、画像はスキップされます。テキストコンテンツを含む PDF 文書をレンダリングする際に流動レイアウトを使用してください。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#create-html-with-fluid-layout) を参照してください。

### 関連項目

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
