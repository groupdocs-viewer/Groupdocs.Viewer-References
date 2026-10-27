---
title: "CadOptions クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "CAD 図面のレンダリングオプション。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

CAD 図面のレンダリングオプション。

詳細情報やコード例については、Render CAD drawings and models as HTML, PDF, and image files と Specify rendering options for CAD files のドキュメントをご覧ください。

CadOptions 型は次のメンバーを公開します：

### メソッド
| メソッド | 説明 |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | 高さでレンダリングするための CadOptions インスタンスを初期化します。 |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | スケール係数でレンダリングするための CadOptions インスタンスを初期化します。 |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | 幅でレンダリングするための [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) クラスのインスタンスを初期化します。 |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | 幅と高さでレンダリングするための CadOptions クラスのインスタンスを初期化します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | 画像の背景色です。 |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | すべての CAD フォーマットに対してパフォーマンス重視の変換モードを有効にするフラグです。True に設定すると変換が高速化しますが、出力品質が低下します。最高品質を得るためのデフォルトは False です。 |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | 出力結果の高さ（ピクセル単位）です。 |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | レンダリングする CAD 図面レイヤーです。 |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | レンダリングする特定のレイアウト名です。レイアウト名は大文字小文字を区別します。 |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | PC3 プロッタ設定ファイルです。 |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | CAD ドキュメントからのレイアウトをレンダリングするかどうかを示すフラグです。 |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | スケール係数です。1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | 描画する領域。 |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | 出力結果の幅（ピクセル単位）。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # CAD ファイルを読み込む
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        # 幅でレンダリングし、パフォーマンスモードを有効にする
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
