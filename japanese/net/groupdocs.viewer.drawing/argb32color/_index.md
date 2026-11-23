---
title: "Argb32Color"
second_title: "GroupDocs.Viewer for .NET API リファレンス"
description: "ARGB形式で各チャンネル（Alpha、Red、Green、Blue）8ビットずつ使用する32ビットカラーを表します。透過をサポートします。"
type: docs
weight: 950
url: /ja/net/groupdocs.viewer.drawing/argb32color/
---

## Argb32Color structure

ARGB 形式の 32 ビットカラーを表し、各チャンネル（Alpha、Red、Green、Blue）に 8 ビットずつ割り当てられます。透過をサポートします。

```csharp
public struct Argb32Color : IEquatable<Argb32Color>, IEquatable<Rgb24Color>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [A](../../groupdocs.viewer.drawing/argb32color/a) { get; } | カラーのアルファ部分を8ビット符号なし整数 [0..255] として取得します。 |
| [Alpha](../../groupdocs.viewer.drawing/argb32color/alpha) { get; } | カラーのアルファ部分を (0..1) の範囲で割合として取得します。 |
| [B](../../groupdocs.viewer.drawing/argb32color/b) { get; } | カラーのブルー部分を8ビット符号なし整数 [0..255] として取得します。 |
| [G](../../groupdocs.viewer.drawing/argb32color/g) { get; } | カラーのグリーン部分を8ビット符号なし整数 [0..255] として取得します。 |
| [IsDefault](../../groupdocs.viewer.drawing/argb32color/isdefault) { get; } | この [`Argb32Color`](../argb32color) インスタンスがデフォルト（Transparent）かどうかを示します - すべての4チャンネルが0に設定されています。[`IsEmpty`](./isempty) と同等です。 |
| [IsEmpty](../../groupdocs.viewer.drawing/argb32color/isempty) { get; } | この [`Argb32Color`](../argb32color) カラーインスタンスが未初期化かどうかを示します - すべての4チャンネルが0に設定されています。Default と Transparent と同等です。[`IsDefault`](./isdefault) と同等です。 |
| [IsFullyOpaque](../../groupdocs.viewer.drawing/argb32color/isfullyopaque) { get; } | この [`Argb32Color`](../argb32color) インスタンスが透過なしで完全に不透明かどうかを示します（Alphaチャンネルが最大値です）。 |
| [IsFullyTransparent](../../groupdocs.viewer.drawing/argb32color/isfullytransparent) { get; } | この [`Argb32Color`](../argb32color) インスタンスが完全に透過しているかどうかを示します - Alphaチャンネルが最小（0）値であるため、他の R、G、B チャンネルは視覚的な効果がありません。 |
| [IsTranslucent](../../groupdocs.viewer.drawing/argb32color/istranslucent) { get; } | この [`Argb32Color`](../argb32color) インスタンスが半透明かどうかを示します（完全に透明ではなく、完全に不透明でもありません） |
| [R](../../groupdocs.viewer.drawing/argb32color/r) { get; } | 色の赤の部分を 8 ビット符号なし整数 [0..255] として取得します |
| [Value](../../groupdocs.viewer.drawing/argb32color/value) { get; } | 色の Int32 値を 32 ビット符号付き整数として取得します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromArgb](../../groupdocs.viewer.drawing/argb32color/fromargb)(int) | `System.Drawing.Color.ToArgb()` メソッドで生成される値と互換性のある、32 ビットコンポーネント（アルファ、赤、緑、青）値から [`Argb32Color`](../argb32color) インスタンスを作成します |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha)(Argb32Color, byte) | 指定された値から新しい [`Argb32Color`](../argb32color) インスタンスを作成しますが、アルファ（不透明度）値は再定義されます |
| static [FromOtherWithAlpha](../../groupdocs.viewer.drawing/argb32color/fromotherwithalpha#fromotherwithalpha_1)(Rgb24Color, byte) | 指定された [`Rgb24Color`](../rgb24color) から新しい [`Argb32Color`](../argb32color) インスタンスを作成しますが、アルファ（不透明度）値は指定されたものを使用します |
| static [FromRgb](../../groupdocs.viewer.drawing/argb32color/fromrgb)(byte, byte, byte) | 指定された赤、緑、青チャンネルから [`Argb32Color`](../argb32color) 値を作成し、アルファチャンネルは完全に不透明にします |
| static [FromRgba](../../groupdocs.viewer.drawing/argb32color/fromrgba)(byte, byte, byte, byte) | 指定された赤、緑、青、アルファチャンネルから [`Argb32Color`](../argb32color) 値を作成します |
| static [FromSingleValueRgb](../../groupdocs.viewer.drawing/argb32color/fromsinglevaluergb)(byte) | 単一の値から完全に不透明 (A=255) な色を作成し、その値はすべてのチャンネルに適用されます |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals)(Argb32Color) | この色と指定された [`Argb32Color`](../argb32color) 色が等しいかどうかをチェックします |
| override [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_2)(object) | この色を指定されたキャストされていない値と比較します |
| [Equals](../../groupdocs.viewer.drawing/argb32color/equals#equals_1)(Rgb24Color) | この色と指定された [`Rgb24Color`](../rgb24color) 色が等しいかどうかをチェックします |
| [GetBrightness](../../groupdocs.viewer.drawing/argb32color/getbrightness)() | この [`Argb32Color`](../argb32color) インスタンスの色相・彩度・明度 (HSL) の明度/輝度を返します。 |
| override [GetHashCode](../../groupdocs.viewer.drawing/argb32color/gethashcode)() | 現在の色を定義するハッシュコードを返します。GetHashCode とは互換性がありません |
| [GetHue](../../groupdocs.viewer.drawing/argb32color/gethue)() | この [`Argb32Color`](../argb32color) インスタンスの色相・彩度・明度 (HSL) の色相値（度単位）を返します。R == G == B の場合、色相は意味を持たず、返り値は 0 です。 |
| [GetSaturation](../../groupdocs.viewer.drawing/argb32color/getsaturation)() | この [`Argb32Color`](../argb32color) インスタンスの色相・彩度・明度 (HSL) の彩度 |
| [ToArgb](../../groupdocs.viewer.drawing/argb32color/toargb)() | この [`Argb32Color`](../argb32color) インスタンスの ARGB 値を返します。`System.Drawing.Color.ToArgb()` メソッドと互換性があります |
| [ToHexRGB](../../groupdocs.viewer.drawing/argb32color/tohexrgb)() | この [`Argb32Color`](../argb32color) インスタンスを 16 進表記 `##RRGGBB`（アルファチャンネルなし）の文字列にシリアライズします |
| [ToHexRGBA](../../groupdocs.viewer.drawing/argb32color/tohexrgba)() | この [`Argb32Color`](../argb32color) インスタンスを 16 進表記 `##RRGGBBAA`（アルファチャンネルあり）の文字列にシリアライズします |
| [ToRGB](../../groupdocs.viewer.drawing/argb32color/torgb)() | この [`Argb32Color`](../argb32color) インスタンスを 'rgb' CSS 関数表記にシリアライズします。シリアライズ時にこの色のアルファチャンネルは省略されます。 |
| [ToRGBA](../../groupdocs.viewer.drawing/argb32color/torgba)() | この [`Argb32Color`](../argb32color) インスタンスを 'rgba' CSS 関数表記にシリアライズします |
| override [ToString](../../groupdocs.viewer.drawing/argb32color/tostring)() | この [`Argb32Color`](../argb32color) インスタンスを、半透明度に応じて最適な CSS 関数表記にシリアライズします |
| [operator ==](../../groupdocs.viewer.drawing/argb32color/op_equality#op_equality) | 2つの [`Argb32Color`](../argb32color) 色を比較し、両者が一致するかどうかを示すブール値を返します。（2 つの演算子） |
| [explicit operator](../../groupdocs.viewer.drawing/argb32color/op_explicit) | 32 ビットの [`Argb32Color`](../argb32color) を 24 ビットの [`Rgb24Color`](../rgb24color) に明示的にキャストします。ソースの [`Argb32Color`](../argb32color) のアルファチャンネルは、[`Rgb24Color`](../rgb24color) が透過をサポートしていないため、キャスト後に失われます。 |
| [implicit operator](../../groupdocs.viewer.drawing/argb32color/op_implicit) | 24 ビットの [`Rgb24Color`](../rgb24color) を 32 ビットの [`Argb32Color`](../argb32color) に暗黙的にキャストします。出力の [`Argb32Color`](../argb32color) のアルファチャンネルは `255` に設定され、完全に不透明になります。 |
| [operator !=](../../groupdocs.viewer.drawing/argb32color/op_inequality#op_inequality) | 2つの[`Argb32Color`](../argb32color)カラーを比較し、2つが一致しないかを示すブール値を返します。(2 演算子) |

## フィールド

| 名前 | 説明 |
| --- | --- |
| static readonly [Empty](../../groupdocs.viewer.drawing/argb32color/empty) | チャンネル情報がなく、完全に透明な空のカラーを返します。'[`Transparent`](./transparent)' と同じです。デフォルト値。 |
| static readonly [Transparent](../../groupdocs.viewer.drawing/argb32color/transparent) | 完全に透明な空のカラーです。デフォルトの'[`Empty`](./empty)' カラー値と同じです。 |

### 備考

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

### 関連項目

* struct [Rgb24Color](../rgb24color)
* namespace [GroupDocs.Viewer.Drawing](../../groupdocs.viewer.drawing)
* assembly [GroupDocs.Viewer](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.Viewer.dll 用に生成されました -->
