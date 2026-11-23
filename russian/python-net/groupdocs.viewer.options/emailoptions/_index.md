---
title: "Класс EmailOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Содержит опции для рендеринга электронных сообщений."
type: docs
url: /ru/python-net/groupdocs.viewer.options/emailoptions/
is_root: false
weight: 40
---


## EmailOptions class

Содержит опции для рендеринга электронных сообщений.

GroupDocs.Viewer поддерживает класс EmailOptions, который позволяет задавать различные параметры для отображения электронных сообщений. Чтобы получить доступ к этим параметрам, используйте свойство EmailOptions в одном из следующих классов параметров просмотра, в зависимости от требуемого формата вывода:

- [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
- [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
- [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
- [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)

Тип EmailOptions предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/emailoptions/__init__/) | Инициализирует экземпляр класса [`EmailOptions`](/viewer/python-net/groupdocs.viewer.options/emailoptions/). |

### Свойства
| Свойство | Описание |
| :- | :- |
| [date_time_format](/viewer/python-net/groupdocs.viewer.options/emailoptions/date_time_format/) | Формат времени (может включать часовой пояс). Если не установлен, используется текущий системный формат. |
| [field_text_map](/viewer/python-net/groupdocs.viewer.options/emailoptions/field_text_map/) | Отображение между полем сообщения электронной почты [`Field`](/viewer/python-net/groupdocs.viewer.options/field/) и текстовым представлением поля. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/emailoptions/page_size/) | Размер выходной страницы. |
| [time_zone_offset](/viewer/python-net/groupdocs.viewer.options/emailoptions/time_zone_offset/) | Смещение часового пояса сообщения. |

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
