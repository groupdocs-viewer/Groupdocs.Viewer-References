---
title: "Класс PdfOptimizationOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет опции оптимизации PDF, применяемые к выходному PDF‑файлу."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

Представляет опции оптимизации PDF, применяемые к выходному PDF‑файлу.

Для получения деталей и примеров кода см. страницу документации.

Тип PdfOptimizationOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | Инициализирует значения по умолчанию параметра MaxResolution до 300 и параметра ImageQuality до 100. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | Свойство позволяет сжимать изображения в выходном PDF‑файле. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | Свойство позволяет преобразовать выходной PDF‑файл в градации серого. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | Качество изображения в выходном PDF‑файле, выраженное в процентах. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | Свойство позволяет оптимизировать выходной PDF‑файл для онлайн‑просмотра в веб‑браузере. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | Максимальное разрешение в выходном PDF‑файле. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | Свойство, позволяющее оптимизировать электронные таблицы в PDF‑файлах. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | Свойство позволяет удалять аннотации из выходного PDF‑файла. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | Свойство позволяет удалять поля формы из PDF‑файла. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | Свойство удаляет неиспользуемые (осиротевшие) объекты из PDF‑файла. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | Свойство удаляет неиспользуемые (осиротевшие) потоки из PDF‑файла, которые указаны в словаре ресурсов страниц, но никогда не используются в содержимом страниц. Отключено по умолчанию (`False`); установка значения `True` уменьшает размер выходного PDF. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | Свойство позволяет установить максимальное разрешение в выходном PDF‑файле. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | Свойство создает подмножества шрифтов в выходном PDF‑файле. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # Включить линейризацию для более быстрой веб‑превью
        view_options.pdf_optimization_options.lineriaze = True
        # Удалите аннотации и поля формы, чтобы уменьшить размер
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
