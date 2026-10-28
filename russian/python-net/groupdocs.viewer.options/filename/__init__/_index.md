---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует экземпляр класса FileName."
type: docs
url: /ru/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Инициализирует экземпляр класса [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Имя файла. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `file_name` имеет значение None. |

### Пример

```python
from groupdocs.viewer.options import FileName

# Создайте экземпляр FileName с пользовательским именем архива
custom_name = FileName("Sample Files")
```

### См. также
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
