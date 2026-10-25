---
title: "WrapImagesInSvg"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを有効にします。"
type: docs
weight: 110
url: /ja/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを有効にします。

```csharp
public bool WrapImagesInSvg { get; set; }
```

### 備考

デフォルトでは、PDF およびページレイアウトファイルを HTML にレンダリングする際、すべての画像が 1 つの PNG 画像としてレンダリングされます。レンダリングされた PNG 画像は出力 HTML ドキュメントの背景として使用されます。

このオプションは、埋め込みおよび外部リソース付きで HTML に [PDF and Page Layout file formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) をレンダリングする際に利用可能です。出力 HTML ドキュメント内の各画像を SVG タグでラップすることができます。デフォルト値は `false` です。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files) を参照してください。

### 関連項目

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
