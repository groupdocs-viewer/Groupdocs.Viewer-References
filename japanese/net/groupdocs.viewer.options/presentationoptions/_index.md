---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "プレゼンテーションのレンダリングオプションを含みます。詳細はドキュメント https//docs.groupdocs.com/viewer/net/renderpresentations/ を参照してください。"
type: docs
weight: 460
url: /ja/net/groupdocs.viewer.options/presentationoptions/
---

## PresentationOptions class

プレゼンテーションのレンダリング オプションが含まれています。詳細については、[documentation](https://docs.groupdocs.com/viewer/net/render-presentations/) を参照してください。

```csharp
public class PresentationOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PresentationOptions](presentationoptions)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [RenderHeaderFooterPlaceholders](../../groupdocs.viewer.options/presentationoptions/renderheaderfooterplaceholders) { get; set; } | スライドのヘッダーとフッターのプレースホルダーのレンダリングを有効にします。デフォルトでは無効 (`false`) です。このオプションはプレゼンテーションのすべての4つのレンダリングモード（HTML、PDF、PNG、JPEG）に適用されます。[`RenderToPureHtml`](./rendertopurehtml) を使用してプレゼンテーションを純粋な HTML/CSS マークアップにレンダリングする場合は適用されません。 |
| [RenderToPureHtml](../../groupdocs.viewer.options/presentationoptions/rendertopurehtml) { get; set; } | プレゼンテーションドキュメント用の新しい HTML レンダリングモードを有効にします — このモードでは、プレゼンテーションファイルが **pure HTML/CSS markup** にレンダリングされ、SVG 画像は使用されません。デフォルトでは無効 (`false`) で、既存の SVG ベースの HTML レンダラーが使用されます。 |
| [Resolution](../../groupdocs.viewer.options/presentationoptions/resolution) { get; set; } | プレゼンテーション画像の解像度（HTML/PDF へのレンダリング時のみ）。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
