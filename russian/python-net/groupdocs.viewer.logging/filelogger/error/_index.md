---
title: "error метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Записывает сообщение об ошибке в консоль."
type: docs
url: /ru/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Записывает сообщение об ошибке в консоль. Сообщения журнала ошибок предоставляют информацию о непоправимых событиях в работе приложения.

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
