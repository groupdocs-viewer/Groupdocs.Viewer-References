---
title: "__init__ المُنشئ"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يقوم بتهيئة نسخة من الفئة Tile."
type: docs
url: /ar/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

يُنشئ مثيلاً من الفئة [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

للتفاصيل، راجع الوثائق.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| start_point_x | `int` | إحداثي X لأدنى نقطة يسارية في الرسم حيث يبدأ البلاط. |
| start_point_y | `int` | إحداثي Y لأدنى نقطة يسارية في الرسم حيث يبدأ البلاط. |
| width | `int` | عرض البلاط بالبكسل. |
| height | `int` | ارتفاع البلاط بالبكسل. |

### مثال

```python
from groupdocs.viewer.options import Tile

# تعريف معلمات Tile
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# إنشاء Tile يمثل جزءًا من الرسم
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### انظر أيضًا
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
