---
title: "trace метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает трассировочное сообщение в журнал."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/filelogger/trace/
is_root: false
weight: 1040
---


## trace {#message}

Записывает трассировочное сообщение в журнал. Трассировочные сообщения журнала предоставляют общую полезную информацию о работе приложения.

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
