---
title: "Класс SpreadsheetOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Опции для рендеринга электронных таблиц."
type: docs
url: /ru/python-net/groupdocs.viewer.options/spreadsheetoptions/
is_root: false
weight: 280
---


## SpreadsheetOptions class

Опции для рендеринга электронных таблиц.

Для получения подробностей см. дочерние элементы темы Render spreadsheet files.

Тип SpreadsheetOptions раскрывает следующие члены:

### Методы
| Метод | Описание |
| :- | :- |
| [for_one_page_per_sheet](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_one_page_per_sheet/) | Инициализирует экземпляр [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) для рендеринга всего листа в одну страницу. |
| [for_rendering_by_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_by_page_breaks/) | Инициализирует экземпляр [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) с настройкой разделения листов на страницы по разрывам страниц. |
| [for_rendering_print_area](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area/) | Инициализирует экземпляр класса [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) только для рендеринга областей печати. |
| [for_rendering_print_area_and_page_breaks](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_rendering_print_area_and_page_breaks/) | Инициализирует экземпляр класса [`SpreadsheetOptions`](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/) для рендеринга областей печати и разрывов страниц. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page) | Инициализирует экземпляр SpreadsheetOptions для рендеринга листа по страницам. |
| [for_split_sheet_into_pages](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages/#count_rows_per_page-count_columns_per_page) | Инициализирует экземпляр SpreadsheetOptions для рендеринга листа по страницам. |
| [for_split_sheet_into_pages_int32](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/for_split_sheet_into_pages_int32/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/bottom_margin/) | Нижнее поле страницы при конвертации в PDF. |
| [count_columns_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_columns_per_page/) | Количество столбцов, включаемых на каждую страницу при разделении листа на страницы. |
| [count_rows_per_page](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/count_rows_per_page/) | Количество строк, включаемых на каждую страницу при разделении листа на страницы. |
| [detect_separator](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/detect_separator/) | Свойство включает обнаружение разделителя для файлов CSV/TSV. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/horizontal_resolution/) | Горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге таблиц в форматы PNG или JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/left_margin/) | Левое поле страницы при конвертации в PDF. |
| [render_grid_lines](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_grid_lines/) | Свойство включает рендеринг линий сетки. |
| [render_headings](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_headings/) | Свойство включает рендеринг заголовков. |
| [render_hidden_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_columns/) | Свойство включает рендеринг скрытых столбцов. |
| [render_hidden_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/render_hidden_rows/) | Свойство включает отображение скрытых строк. |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/right_margin/) | Правый отступ страницы при конвертации в PDF. |
| [skip_empty_columns](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_columns/) | Свойство отключает отображение пустых столбцов. |
| [skip_empty_rows](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/skip_empty_rows/) | Свойство отключает отображение пустых строк. |
| [text_overflow_mode](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/text_overflow_mode/) | Режим переполнения текста при отображении электронных таблиц в HTML. По умолчанию используется `TextOverflowMode.OverlayIfNextIsEmpty`, который имитирует поведение MS Excel по умолчанию. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/top_margin/) | Верхний отступ страницы при конвертации в PDF. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/spreadsheetoptions/vertical_resolution/) | Вертикальное разрешение генерируемых изображений в точках на дюйм. Этот параметр используется только при отображении электронных таблиц в форматах PNG или JPEG. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    # Включить отображение линий сетки в электронной таблице.
    view_options.spreadsheet_options.render_grid_lines = True
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
