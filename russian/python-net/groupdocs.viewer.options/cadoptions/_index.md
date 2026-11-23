---
title: "Класс CadOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции для рендеринга чертежей CAD."
type: docs
url: /ru/python-net/groupdocs.viewer.options/cadoptions/
is_root: false
weight: 30
---


## CadOptions class

Опции для рендеринга чертежей CAD.

Для получения дополнительной информации и примеров кода см. документацию Render CAD drawings and models as HTML, PDF, and image files и Specify rendering options for CAD files.

Тип CadOptions раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [for_rendering_by_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/#height) | Инициализирует экземпляр CadOptions для рендеринга по высоте. |
| [for_rendering_by_scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/#scale_factor) | Инициализирует экземпляр CadOptions для рендеринга по коэффициенту масштабирования. |
| [for_rendering_by_width](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/#width) | Инициализирует экземпляр класса [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) для рендеринга по ширине. |
| [for_rendering_by_width_and_height](/viewer/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width_and_height/#width-height) | Инициализирует экземпляр класса CadOptions для рендеринга по ширине и высоте. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [background_color](/viewer/python-net/groupdocs.viewer.options/cadoptions/background_color/) | Цвет фона изображения. |
| [enable_performance_conversion_mode](/viewer/python-net/groupdocs.viewer.options/cadoptions/enable_performance_conversion_mode/) | Флаг, который включает режим конвертации, ориентированный на производительность, для всех форматов CAD; установка его в True ускоряет конвертацию за счёт снижения качества вывода; по умолчанию False для максимального качества. |
| [height](/viewer/python-net/groupdocs.viewer.options/cadoptions/height/) | Высота результирующего вывода (в пикселях). |
| [layers](/viewer/python-net/groupdocs.viewer.options/cadoptions/layers/) | Слои чертежа CAD для рендеринга. |
| [layout_name](/viewer/python-net/groupdocs.viewer.options/cadoptions/layout_name/) | Имя конкретного макета для рендеринга. Имя макета чувствительно к регистру. |
| [pc3_file](/viewer/python-net/groupdocs.viewer.options/cadoptions/pc3_file/) | Файл конфигурации плоттера PC3. |
| [render_layouts](/viewer/python-net/groupdocs.viewer.options/cadoptions/render_layouts/) | Флаг, указывающий, следует ли рендерить макеты из документа CAD. |
| [scale_factor](/viewer/python-net/groupdocs.viewer.options/cadoptions/scale_factor/) | Коэффициент масштабирования. Значение больше 1 увеличивает результат вывода; значение от 0 до 1 уменьшает результат вывода. |
| [tiles](/viewer/python-net/groupdocs.viewer.options/cadoptions/tiles/) | Области чертежа для рендеринга. |
| [width](/viewer/python-net/groupdocs.viewer.options/cadoptions/width/) | Ширина результирующего вывода (в пикселях). |

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
        # Отрисовка по ширине и включение режима производительности
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True

        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
