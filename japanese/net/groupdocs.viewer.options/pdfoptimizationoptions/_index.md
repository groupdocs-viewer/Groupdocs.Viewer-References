---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "出力 PDF ファイルに適用する PDF 最適化オプションを含みます。詳細とコードサンプルについては、このページhttps//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ とその子ページをご覧ください。"
type: docs
weight: 400
url: /ja/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

出力 PDF ファイルに適用する PDF 最適化オプションが含まれています。詳細とコードサンプルについては、この [page](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) とその子項目を参照してください。

```csharp
public class PdfOptimizationOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | MaxResolution オプションのデフォルト値を 300、ImageQuality オプションのデフォルト値を 100 に設定します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | 出力 PDF ファイルの画像圧縮を有効にします。 |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | 出力 PDF ファイルをグレースケールに変換することを有効にします。 |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | 出力 PDF ファイルの画像品質を（パーセントで）設定します。 |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | ウェブブラウザーでのオンライン閲覧用に、出力 PDF ファイルの最適化を有効にします。 |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | 出力 PDF ファイルの最大解像度を設定します。 |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | PDF ファイル内のスプレッドシートの最適化を有効にします。 |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | 出力 PDF ファイルから注釈を削除することを有効にします。 |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | PDF ファイルからフォームフィールドを削除することを有効にします。 |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | PDF ファイルから未使用（孤立）オブジェクトを削除します。これらは PDF ドキュメントに配置されていますが、任意のページのリソース辞書から参照されておらず、全く使用されていません。このプロパティを有効にすると（`true`）、出力 PDF ドキュメントのサイズが縮小します。デフォルトでは無効（`false`）です。 |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | PDF ファイルから未使用（孤立）ストリームを削除します。これらはページのリソース辞書から参照されていますが、実際にはページ内容で使用されていません。デフォルトでは無効（`false`）で、有効にすると（`true`）出力 PDF ドキュメントのサイズが縮小します。 |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | 出力 PDF ファイルの最大解像度の設定を有効にします。 |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | 出力 PDF ファイルのフォントをサブセット化します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
