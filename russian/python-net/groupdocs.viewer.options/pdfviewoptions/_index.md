---
title: "Класс PdfViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет опции для рендеринга документов в формат PDF."
type: docs
url: /ru/python-net/groupdocs.viewer.options/pdfviewoptions/
is_root: false
weight: 170
---


## PdfViewOptions class

Представляет опции для рендеринга документов в формат PDF.

Для подробностей см. документацию.

Тип PdfViewOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream) | Инициализирует экземпляр [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#create_file_stream-release_file_stream) | Инициализирует новый экземпляр PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#file_stream_factory) | Инициализирует экземпляр PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/) | Инициализирует экземпляр PdfViewOptions. |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/#output_file_path) | Инициализирует экземпляр класса [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/). |

### Методы
| Метод | Описание |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/) | Применяет вращение по часовой стрелке к странице. (унаследовано от [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) | (унаследовано от [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |

### Свойства
| Свойство | Описание |
| :- | :- |
| [image_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_height/) | Высота выходного изображения в пикселях. |
| [image_max_height](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_height/) | Максимальная высота выходного изображения в пикселях. |
| [image_max_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_max_width/) | Максимальная ширина выходного изображения в пикселях. |
| [image_width](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/image_width/) | Ширина выходного изображения в пикселях. |
| [pdf_optimization_options](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/pdf_optimization_options/) | Свойство pdf_optimization_options предоставляет доступ к экземпляру [`PdfOptimizationOptions`](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/), который уменьшает размер выходного PDF‑файла, применяя техники оптимизации. |
| [security](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/security/) | Параметры безопасности для выходного PDF‑документа. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Параметры представления архивных файлов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Параметры просмотра чертежей CAD. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Шрифт по умолчанию для документа, используемый при рендеринге, когда требуемый шрифт отсутствует. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Параметры просмотра электронных сообщений. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Параметры просмотра файлов хранилища почты. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Параметры просмотра файлов данных Microsoft Outlook. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | Поворот страницы. (унаследовано от [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | Параметры просмотра PDF‑документов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | Параметры просмотра файлов презентаций. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | Параметры просмотра файлов управления проектами. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | Свойство отключает рендеринг комментариев, когда установлено в True. По умолчанию оно False, поэтому все комментарии отображаются. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | Свойство включает или отключает рендеринг комментариев. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | Свойство включает рендеринг скрытых страниц. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | Свойство включает рендеринг заметок и аннотаций для некоторых форматов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | Параметры просмотра файлов электронных таблиц. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | Текстовые параметры для рендеринга текстовых файлов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | Параметры просмотра файлов Visio. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Текстовый водяной знак, применяемый к каждой странице. (унаследовано от [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Параметры просмотра веб‑файлов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Параметры просмотра файлов обработки текста. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Guides
Руководства по задачам, использующие `PdfViewOptions`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
