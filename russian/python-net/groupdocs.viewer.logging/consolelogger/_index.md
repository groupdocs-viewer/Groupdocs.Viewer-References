---
title: "Класс ConsoleLogger"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает сообщения журнала в консоль."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/consolelogger/
is_root: false
weight: 10
---


## ConsoleLogger class

Записывает сообщения журнала в консоль.

Тип ConsoleLogger раскрывает следующие члены:

### Конструкторы
| Конструктор | Описание |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.logging/consolelogger/__init__/) |  |

### Методы
| Метод | Описание |
| :- | :- |
| [error](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error/#message-exception) | Записывает сообщение об ошибке в консоль. |
| [error_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_file/) |  |
| [error_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/error_string/) |  |
| [trace](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace/#message) | Записывает трассировочное сообщение в консоль. |
| [trace_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_file/) |  |
| [trace_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/trace_string/) |  |
| [warning](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning/#message) | Записывает предупреждающее сообщение в консоль. |
| [warning_file](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_file/) |  |
| [warning_string](/viewer/python-net/groupdocs.viewer.logging/consolelogger/warning_string/) |  |

### Пример

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources("output/page_{0}.html")
    viewer.view(html_options)
```

### См. также
* module [`groupdocs.viewer.logging`](/viewer/python-net/groupdocs.viewer.logging/)
