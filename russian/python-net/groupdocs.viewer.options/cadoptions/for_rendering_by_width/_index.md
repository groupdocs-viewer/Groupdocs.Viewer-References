---
title: "метод for_rendering_by_width"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса CadOptions для отображения по ширине."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Инициализирует экземпляр класса [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) для рендеринга по ширине.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | `int` | Ширина результирующего вывода (в пикселях). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `width` меньше или равен нулю. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Загрузить файл CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### См. также
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
