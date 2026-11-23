---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "PDF ドキュメントのレンダリング用オプションを含みます。詳細については、ドキュメント https//docs.groupdocs.com/viewer/net/renderpdfdocuments/ を参照してください。"
type: docs
weight: 410
url: /ja/net/groupdocs.viewer.options/pdfoptions/
---

## PdfOptions class

PDF ドキュメントへのレンダリング オプションが含まれています。詳細については、[documentation](https://docs.groupdocs.com/viewer/net/render-pdf-documents/) を参照してください。

```csharp
public class PdfOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfOptions](pdfoptions)() | [`PdfOptions`](../pdfoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | ページレンダリング中の正確なシンボル位置決めのために、シンボルのグルーピングを無効にします。 |
| [DisableCopyProtection](../../groupdocs.viewer.options/pdfoptions/disablecopyprotection) { get; set; } | HTML へのレンダリング時にコンテンツのコピー保護をオフにします。 |
| [DisableFontLicenseVerifications](../../groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications) { get; set; } | 現在の XPS/OXPS ドキュメント内のすべてのフォントに対するライセンス制限を無効にします。 |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | フォントヒンティングを有効にします。 |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | HTML へのレンダリング時に、元の PDF ドキュメントの Z オーダーでテキストとグラフィックのレンダリングを有効にします。 |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | PDF と EPUB ドキュメントを固定レイアウトで HTML にレンダリングすることを有効にします。 |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | HTML へのレンダリング時に画像リソースの出力画像品質を設定します。デフォルトの品質は `Low` です。 |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | 出力ページサイズを元の PDF ドキュメントのページサイズと同じに設定します。 |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | PDF ファイル内のテキストを HTML 出力で画像としてレンダリングすることを有効にします。 |
| [WrapImagesInSvg](../../groupdocs.viewer.options/pdfoptions/wrapimagesinsvg) { get; set; } | 出力 HTML ドキュメント内の各画像を SVG タグでラップし、出力品質を向上させることを有効にします。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
