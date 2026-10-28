---
title: "Класс FileName"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Имя файла."
type: docs
url: /ru/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Имя файла.

Тип FileName раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Инициализирует экземпляр класса [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Методы
| Метод | Описание |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Возвращает строку, представляющую текущий объект. |

### Поля
| Поле | Описание |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Пустое имя файла. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Имя исходного файла. |

### Пример

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### См. также
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
