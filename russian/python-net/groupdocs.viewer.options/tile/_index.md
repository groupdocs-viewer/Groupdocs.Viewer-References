---
title: "Класс Tile"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет область рисования."
type: docs
url: /ru/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Представляет область рисования.

Для получения подробностей см. документацию по адресу https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Тип Tile раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Инициализирует экземпляр класса [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Методы
| Метод | Описание |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Возвращает координату X самой верхней правой точки на чертеже, где заканчивается плитка. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Возвращает координату Y самой верхней правой точки на чертеже, где заканчивается плитка. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Высота плитки в пикселях. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | Координата X самой нижней левой точки на чертеже, где начинается плитка. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Координата Y самой нижней левой точки на чертеже, где начинается плитка. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Ширина плитки в пикселях. |

### Пример

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

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
