---
title: "Класс ViewInfo"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Представляет информацию представления для общего документа."
type: docs
url: /ru/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Представляет информацию представления для общего документа.

Тип ViewInfo раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Инициализирует новый экземпляр [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Инициализирует новый экземпляр ViewInfo. |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Возвращает строку, представляющую текущий объект. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Тип файла. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Список страниц для просмотра. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### См. также
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
