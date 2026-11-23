---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса Tile."
type: docs
url: /ru/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Инициализирует экземпляр класса [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Для подробностей см. документацию.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| start_point_x | `int` | Координата X самой нижней левой точки на чертеже, где начинается плитка. |
| start_point_y | `int` | Координата Y самой нижней левой точки на чертеже, где начинается плитка. |
| width | `int` | Ширина плитки в пикселях. |
| height | `int` | Высота плитки в пикселях. |

### Пример

```python
from groupdocs.viewer.options import Tile

# Определите параметры тайла.
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Создайте тайл, представляющий часть чертежа
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### См. также
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
