---
title: "error метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает сообщение об ошибке."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Записывает сообщение об ошибке.

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
| `ValueError` | Когда `exception` равно None. |

### См. также
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
