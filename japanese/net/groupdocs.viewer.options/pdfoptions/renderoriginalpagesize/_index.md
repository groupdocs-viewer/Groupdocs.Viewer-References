---
title: "RenderOriginalPageSize"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "出力ページサイズを元の PDF ドキュメントのページサイズと同じに設定します。"
type: docs
weight: 90
url: /ja/net/groupdocs.viewer.options/pdfoptions/renderoriginalpagesize/
---

## PdfOptions.RenderOriginalPageSize property

出力ページサイズを元の PDF ドキュメントのページサイズと同じに設定します。

```csharp
public bool RenderOriginalPageSize { get; set; }
```

### 備考

デフォルトでは、GroupDocs.Viewer はレンダリング品質向上のために出力画像のページサイズを計算します。このオプションを有効にすると、出力ページが元の PDF ドキュメントのページサイズ（ピクセル単位）と同じになることが保証されます。デフォルト値は `false` です。

このオプションは PNG または JPG 形式へのレンダリングで利用可能です。

コード例については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#preserve-the-size-of-document-pages) を参照してください。

### 関連項目

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
