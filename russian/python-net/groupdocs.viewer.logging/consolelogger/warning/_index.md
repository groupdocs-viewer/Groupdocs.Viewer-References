---
title: "warning метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает предупреждающее сообщение в консоль."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/consolelogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

Записывает предупреждающее сообщение в консоль.

Сообщения журнала предупреждений предоставляют информацию о неожиданных и восстанавливаемых событиях в потоке выполнения приложения.

```python
def warning(self, message):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| message | `str` | Предупреждающее сообщение. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `message` равно None. |

### См. также
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
