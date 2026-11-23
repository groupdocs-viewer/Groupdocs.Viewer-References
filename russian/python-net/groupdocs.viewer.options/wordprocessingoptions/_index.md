---
title: "Класс WordProcessingOptions"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Содержит параметры рендеринга документов Word."
type: docs
url: /ru/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

Содержит параметры рендеринга документов Word.

Подробности см. в документации по адресу https://docs.groupdocs.com/viewer/net/render-word-documents/.

Тип WordProcessingOptions раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | Инициализирует параметры для рендеринга документов обработки текста. |

### Методы
| Метод | Описание |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | Создаёт и возвращает полную глубокую копию этих параметров. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | Определяет, равен ли указанный экземпляр [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) этому экземпляру. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### Свойства
| Свойство | Описание |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | Нижнее поле страницы. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | Эта опция включает кернинг и другие функции OpenType при рендеринге арабских, ивритских, индийских латинских или кириллических скриптов. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | Горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | Левое поле страницы. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | Расположение нумерации страниц для загруженного документа WordProcessing, которое может принудительно применять нумерацию страниц; по умолчанию это `WordsPageNumberLocation.not_apply`, оставляя документ неизменным. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | Размер выходной страницы. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | Это свойство включает рендеринг отслеживаемых изменений (ревизий). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | Правое поле страницы. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | Верхнее поле страницы в пунктах. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | Эта опция отключает навигацию из оглавления, когда установлена в True для рендеринга HTML или PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | Это свойство определяет, обновляются ли поля определённых типов перед сохранением документа WordProcessing в форматы HTML, PDF, PNG или JPEG. По умолчанию значение True, что означает обновление полей. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | Вертикальное разрешение генерируемых изображений в точках на дюйм, используется только при рендеринге документов WordProcessing в форматы PNG или JPEG. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
