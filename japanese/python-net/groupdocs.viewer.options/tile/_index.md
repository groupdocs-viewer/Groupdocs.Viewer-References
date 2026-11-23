---
title: "Tile クラス"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "描画領域を表します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

描画領域を表します。

詳細については、https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles のドキュメントをご覧ください。

Tile 型は次のメンバーを公開します：

### コンストラクタ
| コンストラクタ | 説明 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) クラスのインスタンスを初期化します。 |

### メソッド
| メソッド | 説明 |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | タイルが終了する描画上の最も右上の点の X 座標を返します。 |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | タイルが終了する描画上の最も右上の点の Y 座標を返します。 |

### プロパティ
| プロパティ | 説明 |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | タイルの高さ（ピクセル単位）。 |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | タイルが開始する描画上の最も左下の点の X 座標。 |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | タイルが開始する描画上の最も左下の点の Y 座標。 |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | タイルの幅（ピクセル単位）。 |

### 例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### 参照
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
