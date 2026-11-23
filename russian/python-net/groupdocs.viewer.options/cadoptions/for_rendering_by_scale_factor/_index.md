---
title: "метод for_rendering_by_scale_factor"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр CadOptions для рендеринга по коэффициенту масштабирования."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Инициализирует экземпляр CadOptions для рендеринга по коэффициенту масштабирования.

Для примера кода см. документацию.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| scale_factor | `float` | Значение больше 1 увеличивает результат вывода; значение между 0 и 1 уменьшает результат вывода. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `scale_factor` меньше или равен нулю. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### См. также
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
