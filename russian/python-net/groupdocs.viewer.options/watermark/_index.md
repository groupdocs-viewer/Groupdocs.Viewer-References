---
title: "Класс Watermark"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет текстовый водяной знак."
type: docs
url: /ru/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Представляет текстовый водяной знак.

Смотрите онлайн‑документацию для получения дополнительной информации.

Тип Watermark раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Инициализирует экземпляр класса [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Цвет водяного знака. Значение по умолчанию — `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Имя шрифта, используемого для водяного знака. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Позиция водяного знака. Значение по умолчанию — `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Размер водяного знака. Значение по умолчанию — [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Текст водяного знака. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Загрузить документ
    with Viewer("sample.docx") as viewer:
        # Создать HTML‑файл.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Добавить водяной знак.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Руководства задач, использующие `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
