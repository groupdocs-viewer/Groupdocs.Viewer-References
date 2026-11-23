---
title: "Метод from_rgb"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Создаёт значение Argb32Color из указанных каналов Red, Green, Blue, при этом канал Alpha устанавливается полностью непрозрачным."
type: docs
url: /ru/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Создаёт значение Argb32Color из указанных каналов Red, Green, Blue, при этом канал Alpha устанавливается полностью непрозрачным.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| red | `int` | Значение канала красного. |
| green | `int` | Значение канала зеленого. |
| blue | `int` | Значение канала синего. |

**Returns:** Argb32Color: New Argb32Color value.

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### См. также
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
