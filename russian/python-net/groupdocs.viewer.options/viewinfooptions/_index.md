---
title: "Класс ViewInfoOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции, используемые для получения информации о представлении."
type: docs
url: /ru/python-net/groupdocs.viewer.options/viewinfooptions/
is_root: false
weight: 330
---


## ViewInfoOptions class

Опции, используемые для получения информации о представлении.

Тип ViewInfoOptions раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/) | Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в HTML. |
| [for_html_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view/#render_single_page) | Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в HTML. |
| [for_html_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_html_view_boolean/) |  |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/) | Инициализирует экземпляр [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) для получения информации о представлении при рендеринге в JPG. |
| [for_jpg_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view/#extract_text) | Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в JPG. |
| [for_jpg_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_jpg_view_boolean/) |  |
| [for_pdf_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_pdf_view/) | Инициализирует экземпляр ViewInfoOptions для получения информации о представлении при рендеринге в PDF. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/) | Инициализирует экземпляр класса [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) для получения информации о представлении при рендеринге в PNG. |
| [for_png_view](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view/#extract_text) | Инициализирует экземпляр класса ViewInfoOptions для получения информации о представлении при рендеринге в PNG. |
| [for_png_view_boolean](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/for_png_view_boolean/) |  |
| [from_html_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_html_view_options/#options) | Инициализирует экземпляр класса ViewInfoOptions на основе объекта HtmlViewOptions. |
| [from_jpg_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_jpg_view_options/#options) | Инициализирует экземпляр [`ViewInfoOptions`](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/) на основе предоставленного [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/). |
| [from_pdf_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_pdf_view_options/#options) | Инициализирует экземпляр ViewInfoOptions из объекта PdfViewOptions. |
| [from_png_view_options](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/from_png_view_options/#options) | Инициализирует экземпляр ViewInfoOptions из объекта PngViewOptions. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [extract_text](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/extract_text/) | Свойство позволяет извлекать текст. |
| [height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/height/) | Высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [max_height](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_height/) | Максимальная высота выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
| [max_width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/max_width/) | Максимальная ширина выходного изображения в пикселях (только для рендеринга в PNG/JPG). |
| [width](/viewer/python-net/groupdocs.viewer.options/viewinfooptions/width/) | Ширина выходного изображения (в пикселях, только для рендеринга в PNG/JPG). |
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
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.pdf") as viewer:
    info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    print("Document type:", info.file_type)
    print("Pages count:", len(info.pages))
```

### Guides
Руководства задач, использующие `ViewInfoOptions`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
