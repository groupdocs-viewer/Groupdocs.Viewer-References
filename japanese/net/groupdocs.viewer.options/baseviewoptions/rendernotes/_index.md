---
title: "RenderNotes"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "一部の形式でノートと注釈の描画を有効にします"
type: docs
weight: 120
url: /ja/net/groupdocs.viewer.options/baseviewoptions/rendernotes/
---

## BaseViewOptions.RenderNotes property

一部の形式でノートと注釈の描画を有効にします

```csharp
public bool RenderNotes { get; set; }
```

### 備考

プレゼンテーションや Microsoft Project ファイルなどの一部の形式にはノートが含まれる場合があります。また、PDF ファイルにはポップアップ注釈（バルーンヒント）があり、デフォルトでは非表示で、PDF ビューアでマウスカーソルを合わせたときにのみ表示されます。デフォルトでは、GroupDocs.Viewer はこのようなノートや注釈をレンダリングしません（`false`）。これを有効にするには、このプロパティを `true` に設定してください。

コード例については、[ドキュメント](https://docs.groupdocs.com/viewer/net/render-presentations/#render-speaker-notes)をご覧ください。

### 関連項目

* class [BaseViewOptions](../../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
