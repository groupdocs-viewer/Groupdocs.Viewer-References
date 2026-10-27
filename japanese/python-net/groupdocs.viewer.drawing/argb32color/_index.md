---
title: "Argb32Color クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "ARGB 形式で 32 ビットカラーを表し、各チャンネル (Alpha、Red、Green、Blue) が 8 ビットです。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/argb32color/
is_root: false
weight: 10
---


## Argb32Color class

ARGB 形式の 32 ビットカラーを表し、各チャンネル（アルファ、赤、緑、青）8 ビットです。透過をサポートします。

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Argb32Color 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/argb32color/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | この色が指定された [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) と等しいかどうかをチェックします。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#other) | この色が指定された [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) と等しいかどうかを判定します。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals/#obj) | この色が指定されたキャストされていない色と等しいかどうかをチェックします。 |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/equals_rgb_24_color/) |  |
| [from_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_argb/#argb) | 32 ビット ARGB 値から Argb32Color インスタンスを作成します。この値は `System.Drawing.Color.ToArgb()` によって生成される値と互換性があります。 |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 指定されたインスタンスから新しい [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスを作成しますが、アルファ（不透明度）値は再定義されます。 |
| [from_other_with_alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha/#other-new_alpha) | 指定された Rgb24Color から新しい Argb32Color インスタンスを作成しますが、アルファ（不透明度）値を指定します。 |
| [from_other_with_alpha_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_argb_32_color/) |  |
| [from_other_with_alpha_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_other_with_alpha_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/#red-green-blue) | 指定された Red、Green、Blue チャンネルから Argb32Color 値を作成し、Alpha チャンネルは完全に不透明に設定されます。 |
| [from_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_rgba/#red-green-blue-alpha) | 指定された red、green、blue、alpha チャンネル値から [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) 値を作成します。 |
| [from_single_value_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/from_single_value_rgb/#value) | すべてのチャンネルに適用される単一バイト値から、完全に不透明 (A=255) なカラーを作成します。 |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_brightness/) | この [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスの Hue‑Saturation‑Lightness (HSL) の明度/輝度を返します。 |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hash_code/) | 現在のカラーを定義するハッシュコードを返します；`System.Drawing.Color.GetHashCode` とは互換性がありません。 |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_hue/) | この [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスの Hue‑Saturation‑Lightness (HSL) の色相値（度）を返します。R == G == B の場合、色相は意味を持たず、メソッドは 0 を返します。 |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/argb32color/get_saturation/) | この [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスの Hue‑Saturation‑Lightness (HSL) の彩度を返します。 |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_argb/) | この [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) インスタンスの ARGB 値を返します。`System.Drawing.Color.ToArgb()` メソッドと互換性があります。 |
| [to_hex_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgb/) | この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスを、アルファチャンネルなしの16進表記 `##RRGGBB` の文字列にシリアライズします。 |
| [to_hex_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_hex_rgba/) | この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスを、アルファチャンネル付きの16進表記 `##RRGGBBAA` の文字列にシリアライズします。 |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgb/) | この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスを、アルファチャンネルを省いた `rgb` CSS関数表記にシリアライズします。 |
| [to_rgba](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_rgba/) | この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスを、`rgba` CSS関数表記にシリアライズします。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/argb32color/to_string/) | Argb32Colorインスタンスを、透明度に応じて最適なCSS関数表記にシリアライズします。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [a](/viewer/python-net/groupdocs.viewer.drawing/argb32color/a/) | 色のアルファ成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |
| [alpha](/viewer/python-net/groupdocs.viewer.drawing/argb32color/alpha/) | 色のアルファ成分を、0..1 の範囲の浮動小数点数として表します。 |
| [b](/viewer/python-net/groupdocs.viewer.drawing/argb32color/b/) | 色の青成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |
| [g](/viewer/python-net/groupdocs.viewer.drawing/argb32color/g/) | 色の緑成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) | このプロパティは、この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスがデフォルト（透明）かどうかを示します。すべてのチャンネルが 0 に設定されていることを意味し、[`Argb32Color.is_empty`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) と同等です。 |
| [is_empty](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_empty/) | このプロパティは、この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスが未初期化（すべてのチャンネルが 0 に設定）かどうかを示します。デフォルトまたは透明色と同等で、[`Argb32Color.is_default`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_default/) と一致します。 |
| [is_fully_opaque](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_opaque/) | このプロパティは、この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスが完全に不透明で、透明性がないか（アルファチャンネルが最大値）を示します。 |
| [is_fully_transparent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_fully_transparent/) | このプロパティは、この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスが完全に透明かどうかを示します。アルファチャンネルが最小（0）値であるため、R、G、B チャンネルは視覚的に影響しません。 |
| [is_translucent](/viewer/python-net/groupdocs.viewer.drawing/argb32color/is_translucent/) | このプロパティは、この[`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)インスタンスが半透明かどうか（完全に透明でもなく、完全に不透明でもない）を示します。 |
| [r](/viewer/python-net/groupdocs.viewer.drawing/argb32color/r/) | 色の赤成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |
| [value](/viewer/python-net/groupdocs.viewer.drawing/argb32color/value/) | 色の 32 ビット符号付き整数表現です。 |

### フィールド
| フィールド | 説明 |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.drawing/argb32color/empty/) | チャネル情報がなく完全に透明な空の色を返します。'' と同等です。デフォルト値です。 |
| [TRANSPARENT](/viewer/python-net/groupdocs.viewer.drawing/argb32color/transparent/) | 完全に透明な空の色です。デフォルトの '' カラー値と同じです。 |

### 例

```python
from groupdocs.viewer.drawing import Argb32Color

# 完全に不透明な黄色 (RGB 255, 255, 0) を作成します
yellow = Argb32Color.from_rgb(255, 255, 0)
```

### 参照
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
