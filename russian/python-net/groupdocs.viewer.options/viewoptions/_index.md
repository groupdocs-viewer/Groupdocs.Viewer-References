---
title: "Класс ViewOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции рендеринга."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewoptions/
is_root: false
weight: 340
---


## ViewOptions class

Опции рендеринга.

Тип ViewOptions раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/#page_number-rotation) | Применяет вращение по часовой стрелке к странице. |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | Вращение страницы. |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | Текстовый водяной знак, который будет применён к каждой странице. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | Параметры представления архивных файлов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | Параметры просмотра чертежей CAD. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | Шрифт по умолчанию для документа, используемый при рендеринге, когда требуемый шрифт отсутствует. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | Параметры просмотра электронных сообщений. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | Параметры просмотра файлов хранилища почты. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | Параметры просмотра файлов данных Microsoft Outlook. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
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
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | Параметры просмотра веб‑файлов. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | Параметры просмотра файлов обработки текста. (наследовано от [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("sample.pptx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.render_notes = True
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
