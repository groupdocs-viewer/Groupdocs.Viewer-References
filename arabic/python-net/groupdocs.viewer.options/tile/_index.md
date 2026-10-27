---
title: "فئة Tile"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل منطقة الرسم."
type: docs
url: /ar/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

يمثل منطقة الرسم.

للتفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

نوع Tile يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | يُنشئ مثيلاً من الفئة [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | يرجع إحداثي X لأعلى نقطة يمينية في الرسم حيث ينتهي البلاط. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | يرجع إحداثي Y لأعلى نقطة يمينية في الرسم حيث ينتهي البلاط. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | ارتفاع البلاط بالبكسل. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | إحداثي X لأدنى نقطة يسارية في الرسم حيث يبدأ البلاط. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | إحداثي Y لأدنى نقطة يسارية في الرسم حيث يبدأ البلاط. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | عرض البلاط بالبكسل. |

### مثال

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

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
