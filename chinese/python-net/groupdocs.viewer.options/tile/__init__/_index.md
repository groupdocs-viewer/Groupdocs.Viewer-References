---
title: "__init__ 构造函数"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "初始化 Tile 类的实例。"
type: docs
url: /zh/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

初始化 [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) 类的实例。

有关详细信息，请参阅文档。

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| start_point_x | `int` | 瓦片开始处绘图中最低左侧点的 X 坐标。 |
| start_point_y | `int` | 瓦片开始处绘图中最低左侧点的 Y 坐标。 |
| width | `int` | 瓦片的宽度（像素）。 |
| height | `int` | 瓦片的高度（像素）。 |

### 示例

```python
from groupdocs.viewer.options import Tile

# 定义瓦片参数
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# 创建表示图形部分的瓦片
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### 另见
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
