---
title: "RemoveComments"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "true に設定するとコメントのレンダリングが無効になります。デフォルトは false で、すべてのコメントが表示されます。"
type: docs
weight: 100
url: /ja/net/groupdocs.viewer.options/baseviewoptions/removecomments/
---

## BaseViewOptions.RemoveComments property

`true` に設定するとコメントの描画が無効になります。デフォルトは `false` で、すべてのコメントが表示されます。

```csharp
public bool RemoveComments { get; set; }
```

### 備考

PDF や WordProcessing などの一部のドキュメント形式にはコメントが含まれる場合があります。デフォルトでは GroupDocs.Viewer がそれらをレンダリングします。このオプションを `true` に設定すると、結果のドキュメントからコメントが除外される可能性があります。

このオプションは、廃止された 'RenderComments' プロパティに代わります。

### 関連項目

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
