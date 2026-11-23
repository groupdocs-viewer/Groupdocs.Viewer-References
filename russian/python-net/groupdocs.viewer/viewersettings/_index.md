---
title: "Класс ViewerSettings"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Определяет параметры для настройки поведения Viewer."
type: docs
url: /ru/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Определяет настройки для кастомизации поведения [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Тип ViewerSettings предоставляет следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Инициализирует новый экземпляр ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Инициализирует новый экземпляр ViewerSettings. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Инициализирует новый экземпляр ViewerSettings. |

### Свойства
| Свойство | Описание |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Реализация кэша, используемая для хранения результатов рендеринга. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Реализация логгера, используемая для ведения журнала (Ошибки, Предупреждения, Трассировки). |

### Пример

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### См. также
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
