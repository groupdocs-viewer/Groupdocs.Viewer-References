---
title: "Класс PdfOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет опции для рендеринга в PDF‑документы."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

Представляет опции для рендеринга в PDF‑документы.

Для подробностей см. документацию.

Тип PdfOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | Инициализирует новый экземпляр класса PdfOptions. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | Свойство отключает группировку символов для точного позиционирования символов во время рендеринга страницы. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | Свойство отключает защиту от копирования контента при рендеринге в HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | Свойство отключает любые лицензионные ограничения для всех шрифтов в текущем документе XPS/OXPS. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | Свойство включает хинтинг шрифтов. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | Свойство включает рендеринг текста и графики в оригинальном порядке слоёв (z-order) PDF‑документа при рендеринге в HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | Опция фиксированного макета включает рендеринг PDF‑ и EPUB‑документов в HTML с фиксированным макетом. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | Качество выходных изображений для ресурсов изображений при рендеринге в HTML. Качество по умолчанию — `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | Размер выходной страницы устанавливается в соответствии с размером страницы исходного PDF‑документа. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | Опция включает рендеринг текста в PDF‑файлах в виде изображения в HTML‑выводе. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | Свойство, которое включает обёртывание каждого изображения в выходном HTML‑документе в тег SVG для повышения качества вывода. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # Включить хинтинг шрифтов при рендеринге страниц PDF в изображения.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
