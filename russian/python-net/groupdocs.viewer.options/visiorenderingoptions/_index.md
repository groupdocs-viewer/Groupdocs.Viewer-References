---
title: "Класс VisioRenderingOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет параметры рендеринга документов Visio."
type: docs
url: /ru/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Представляет параметры рендеринга документов Visio.

Для подробностей см. документацию.

Тип VisioRenderingOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Инициализирует экземпляр класса [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Ширина фигуры; высота рассчитывается автоматически. Значение по умолчанию — 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Свойство отображает только фигуры Visio, а не диаграмму. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Загрузить документ Visio
    with Viewer("map.vsdx") as viewer:
        # Конвертировать файл Visio в PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Отрисовывать только основные формы.
        view_options.visio_rendering_options.render_figures_only = True
        # Укажите ширину формы в пикселях.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
