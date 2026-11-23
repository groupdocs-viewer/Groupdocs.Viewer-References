---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Viewer for Python via .NET API リファレンス"
description: "Tile クラスのインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

[`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) クラスのインスタンスを初期化します。

詳細については、ドキュメントをご覧ください。

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| start_point_x | `int` | タイルが開始する描画上の最も左下の点の X 座標。 |
| start_point_y | `int` | タイルが開始する描画上の最も左下の点の Y 座標。 |
| width | `int` | タイルの幅（ピクセル単位）。 |
| height | `int` | タイルの高さ（ピクセル単位）。 |

### 例

```python
from groupdocs.viewer.options import Tile

# タイルパラメータを定義する
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# 図面の一部を表すタイルを作成する
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### 参照
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
