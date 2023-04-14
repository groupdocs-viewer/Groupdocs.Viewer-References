---
title: CadOptions
second_title: GroupDocs.Viewer for .NET API リファレンス
description: CAD 図面をレンダリングするためのオプションを提供します
type: docs
weight: 290
url: /ja/net/groupdocs.viewer.options/cadoptions/
---
## CadOptions class

CAD 図面をレンダリングするためのオプションを提供します。

```csharp
public class CadOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | 画像背景色 |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | ピクセル単位の出力結果の高さ. |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | レンダリングする CAD 描画レイヤー。 |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | レンダリングする特定のレイアウトの名前。レイアウト名は大文字と小文字が区別されます. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - プロッタ構成ファイル |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | CAD ドキュメントのレイアウトをレンダリングするかどうかを示します。 |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | 1 より大きい値は出力結果を拡大します。 0 から 1 の間の値は、出力結果を小さくします。 |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | レンダリングする描画領域。 |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | ピクセル単位の出力結果の幅. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | の新しいインスタンスを初期化します[`CadOptions`](../cadoptions)高さでレンダリングするためのクラス. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | の新しいインスタンスを初期化します[`CadOptions`](../cadoptions)倍率によるレンダリングのクラス. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | の新しいインスタンスを初期化します[`CadOptions`](../cadoptions) width. でレンダリングするためのクラス |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | の新しいインスタンスを初期化します[`CadOptions`](../cadoptions)幅と高さでレンダリングするためのクラス. |

### 関連項目

* 名前空間 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 組み立て [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->