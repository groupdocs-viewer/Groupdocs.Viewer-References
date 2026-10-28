---
title: "trace метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает трассировочное сообщение."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/ilogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Записывает трассировочное сообщение.

Сообщения журнала трассировки предоставляют в целом полезную информацию о потоке выполнения приложения.

```python
def trace(self, message):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| message | `str` | Сообщение трассировки. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `message` равно None. |

### См. также
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
