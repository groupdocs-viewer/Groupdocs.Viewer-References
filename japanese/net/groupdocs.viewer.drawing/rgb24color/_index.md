---
title: "Rgb24Color"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "RGB 形式で 24 ビットカラーを表し、各チャンネル（Red、Green、Blue）は 8 ビットです。透過はサポートされません。"
type: docs
weight: 970
url: /ja/net/groupdocs.viewer.drawing/rgb24color/
---

## Rgb24Color structure

RGB 形式の 24 ビットカラーを表し、各チャンネル（Red、Green、Blue）に 8 ビットずつ割り当てられます。透過はサポートされません。

```csharp
public struct Rgb24Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [B](../../groupdocs.viewer.drawing/rgb24color/b) { get; } | カラーのブルー部分を8ビット符号なし整数 [0..255] として取得します。 |
| [G](../../groupdocs.viewer.drawing/rgb24color/g) { get; } | カラーのグリーン部分を8ビット符号なし整数 [0..255] として取得します。 |
| [IsDefault](../../groupdocs.viewer.drawing/rgb24color/isdefault) { get; } | この [`Rgb24Color`](../rgb24color) インスタンスがデフォルト（Black）かどうかを示します - すべての 3 チャンネルが 0 に設定されています。 |
| [R](../../groupdocs.viewer.drawing/rgb24color/r) { get; } | 色の赤の部分を 8 ビット符号なし整数 [0..255] として取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromRgb](../../groupdocs.viewer.drawing/rgb24color/fromrgb)(byte, byte, byte) | 指定された Red、Green、Blue チャンネルから 1 つの [`Rgb24Color`](../rgb24color) 値を作成します。 |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals)(Argb32Color) | この色と指定された [`Argb32Color`](../argb32color) 色が等しいかどうかをチェックします |
| override [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_2)(object) | この色を指定されたキャストされていない値と比較します |
| [Equals](../../groupdocs.viewer.drawing/rgb24color/equals#equals_1)(Rgb24Color) | この色と指定された [`Rgb24Color`](../rgb24color) 色が等しいかどうかをチェックします |
| [GetBrightness](../../groupdocs.viewer.drawing/rgb24color/getbrightness)() | この [`Rgb24Color`](../rgb24color) インスタンスの Hue-Saturation-Lightness（HSL） の明度/輝度を返します。 |
| override [GetHashCode](../../groupdocs.viewer.drawing/rgb24color/gethashcode)() | 現在の色を定義するハッシュコードを返します。GetHashCode とは互換性がありません |
| [GetHue](../../groupdocs.viewer.drawing/rgb24color/gethue)() | この[`Rgb24Color`](../rgb24color)インスタンスの Hue-Saturation-Lightness (HSL) の色相値（度単位）を返します。R == G == B の場合、色相は意味を持たず、返り値は 0 です。 |
| [GetSaturation](../../groupdocs.viewer.drawing/rgb24color/getsaturation)() | この[`Rgb24Color`](../rgb24color)インスタンスの Hue-Saturation-Lightness (HSL) の彩度 |
| [ToArgb](../../groupdocs.viewer.drawing/rgb24color/toargb)() | この[`Rgb24Color`](../rgb24color)インスタンスの ARGB 値を返します（Color と互換性あり） |
| [ToHex](../../groupdocs.viewer.drawing/rgb24color/tohex)() | この色を 16 進数文字列として返します |
| [ToRGB](../../groupdocs.viewer.drawing/rgb24color/torgb)() | この[`Rgb24Color`](../rgb24color)インスタンスを 'rgb' CSS 関数表記にシリアライズします。 |
| override [ToString](../../groupdocs.viewer.drawing/rgb24color/tostring)() | この[`Rgb24Color`](../rgb24color)インスタンスを 'rgb(r, g, b)' 形式にシリアライズします。 |
| [operator ==](../../groupdocs.viewer.drawing/rgb24color/op_equality#op_equality_1) | 2 つの[`Rgb24Color`](../rgb24color)カラーを比較し、一致するかどうかを示すブール値を返します。（演算子 2 つ） |
| [operator !=](../../groupdocs.viewer.drawing/rgb24color/op_inequality#op_inequality_1) | 2 つの[`Rgb24Color`](../rgb24color)カラーを比較し、一致しないかどうかを示すブール値を返します。（演算子 2 つ） |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| static class [KnownColors](rgb24color.knowncolors) | CSS 標準で固定されたユニークな名前と値を持つ、すべての\"known colors\"を含みます |

### 備考

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 関連項目

* struct [Argb32Color](../argb32color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
