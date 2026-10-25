---
title: "CadOptions"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "CAD 図面のレンダリングオプションを含みます。詳細情報とコード例については、Render CAD drawings and models as HTML PDF and image files https://docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ と Specify rendering options for CAD files https://docs.groupdocs.com/viewer/net/specifycadrenderingoptions/ を参照してください。"
type: docs
weight: 280
url: /ja/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

CAD 図面のレンダリング オプションが含まれています。詳細情報とコード例については、[Render CAD drawings and models as HTML, PDF, and image files](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) と [Specify rendering options for CAD files](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/) を参照してください。

```csharp
public class CadOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | 画像の背景色。 |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | `true` に設定すると、CAD ファミリ内のすべての形式に対して、パフォーマンス重視の特別な変換モードが有効になります。このモードでは変換速度が大幅に速くなりますが、生成されるドキュメントの品質は著しく低下します。デフォルトでは無効 (`false`) で、生成されるドキュメントの品質はパフォーマンスを犠牲にして可能な限り最高になります。 |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | 出力結果の高さ（ピクセル単位）。 |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | レンダリングする CAD 図面のレイヤー。 |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | レンダリングする特定のレイアウト名。レイアウト名は大文字小文字を区別します。 |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - プロッタ設定ファイル |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | CAD ドキュメントのレイアウトをレンダリングするかどうかのフラグ。 |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | 1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | レンダリングする描画領域。 |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | 出力結果の幅（ピクセル単位）。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | 高さでレンダリングするために、[`CadOptions`](../cadoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | スケール係数でレンダリングするために、[`CadOptions`](../cadoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | 幅でレンダリングするために、[`CadOptions`](../cadoptions) クラスのインスタンスを初期化します。 |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | 幅と高さでレンダリングするために、[`CadOptions`](../cadoptions) クラスのインスタンスを初期化します。 |

### 関連項目

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
