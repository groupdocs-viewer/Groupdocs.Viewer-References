---
title: "DisableCopyProtection"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "HTML へのレンダリング時にコンテンツのコピー保護をオフにします。"
type: docs
weight: 30
url: /ja/net/groupdocs.viewer.options/pdfoptions/disablecopyprotection/
---

## PdfOptions.DisableCopyProtection property

HTML へのレンダリング時にコンテンツのコピー保護をオフにします。

```csharp
public bool DisableCopyProtection { get; set; }
```

### 備考

PDF ファイルを HTML にレンダリングする際にテキストや画像のコピーを防止する保護がある場合、GroupDocs.Viewer は HTML BODY タグに 'inert' 属性を追加します。このオプションのデフォルト値は `false` で、PDF 文書が保護されている場合にのみ 'intent' 属性が追加されることを示します。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection) を参照してください。

### 関連項目

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
