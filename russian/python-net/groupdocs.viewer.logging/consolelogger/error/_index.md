---
title: "error метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает сообщение об ошибке в консоль."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/consolelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Записывает сообщение об ошибке в консоль.

Сообщения журнала ошибок предоставляют информацию о необратимых событиях в потоке выполнения приложения.

```python
def error(self, message, exception):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| message | `str` | Сообщение об ошибке. |
| exception | `Exception` | Исключение. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `exception` равно None. |

### См. также
* class [`ConsoleLogger`](/viewer/python-net/groupdocs.viewer.logging/consolelogger/)
