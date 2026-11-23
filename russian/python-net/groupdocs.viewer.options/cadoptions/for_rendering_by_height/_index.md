---
title: "метод for_rendering_by_height"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр CadOptions для рендеринга по высоте."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Инициализирует экземпляр CadOptions для рендеринга по высоте.

Для примера кода см. документацию.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| height | `int` | Высота результирующего вывода (в пикселях). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `height` меньше или равен нулю. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### См. также
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
