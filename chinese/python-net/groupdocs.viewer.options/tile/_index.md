---
title: "Tile 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示绘图区域."
type: docs
url: /zh/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

表示绘图区域.

有关详细信息，请参阅文档：https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles。

Tile 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | 初始化 [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) 类的实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | 返回瓦片结束处绘图中最高右侧点的 X 坐标。 |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | 返回瓦片结束处绘图中最高右侧点的 Y 坐标。 |

### 属性
| 属性 | 描述 |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | 瓦片的高度（像素）。 |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | 瓦片开始处绘图中最低左侧点的 X 坐标。 |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | 瓦片开始处绘图中最低左侧点的 Y 坐标。 |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | 瓦片的宽度（像素）。 |

### 示例

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

### 另见
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
