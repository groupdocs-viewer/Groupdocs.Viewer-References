---
title: "Rgb24Color クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "各チャンネル（赤、緑、青）8 ビットの 24 ビット RGB カラーを表し、透過はありません。"
type: docs
url: /ja/python-net/groupdocs.viewer.drawing/rgb24color/
is_root: false
weight: 80
---


## Rgb24Color class

各チャンネル（赤、緑、青）8 ビットの 24 ビット RGB カラーを表し、透過はありません。

この型は CSS 操作に役立つように設計されています（ただしこれに限定されません）。詳細はこちら: https://developer.mozilla.org/en-US/docs/Web/CSS/color_value

Rgb24Color 型は次のメンバーを公開します:

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/__init__/) |  |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | この色が指定された [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/) と等しいかどうかを判定します。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#other) | この色と指定された [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) の等価性をチェックします。 |
| [equals](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals/#obj) | この色を指定された未キャストの色と比較します。 |
| [equals_argb_32_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_argb_32_color/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_object/) |  |
| [equals_rgb_24_color](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/equals_rgb_24_color/) |  |
| [from_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/from_rgb/#red-green-blue) | 指定された赤、緑、青のチャンネル値から [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) の値を作成します。 |
| [get_brightness](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_brightness/) | この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスの Hue‑Saturation‑Lightness (HSL) の明度/輝度を返します。 |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hash_code/) | 現在の色を定義するハッシュコードを返します。`System.Drawing.Color.GetHashCode` とは互換性がありません。 |
| [get_hue](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_hue/) | HSL カラースペースにおける色相成分を度数で返します。色がグレースケール (R == G == B) の場合、色相は未定義となり、メソッドは 0 を返します。 |
| [get_saturation](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/get_saturation/) | この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスの Hue‑Saturation‑Lightness (HSL) 彩度。 |
| [to_argb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_argb/) | この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスの ARGB 値を返します（`System.Drawing.Color` と互換性あり）。 |
| [to_hex](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_hex/) | この色を 16 進文字列表現で返します。 |
| [to_rgb](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_rgb/) | この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスを 'rgb' CSS 関数表記にシリアライズします。 |
| [to_string](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/to_string/) | この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスを 'rgb(r, g, b)' 形式にシリアライズします。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [b](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/b/) | 色の青成分を 8 ビット符号なし整数 [0..255] で表します。 |
| [g](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/g/) | 色の緑成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |
| [is_default](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/is_default/) | このプロパティは、この [`Rgb24Color`](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/) インスタンスがデフォルト（黒）かどうかを示します – 3 つのチャンネルすべてが 0 に設定されています。 |
| [r](/viewer/python-net/groupdocs.viewer.drawing/rgb24color/r/) | 色の赤成分を、0..255 の範囲の 8 ビット符号なし整数として表します。 |

### 参照
* module [`groupdocs.viewer.drawing`](/viewer/python-net/groupdocs.viewer.drawing/)
