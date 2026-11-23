---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр Resource."
type: docs
url: /ru/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр Resource.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Инициализирует новый экземпляр Resource.

```python
def __init__(self, file_name, nested):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | `str` | Имя файла ресурса. |
| nested | `bool` | Указывает, находится ли ресурс внутри другого ресурса, например шрифтовый ресурс, который находится в ресурсе CSS или SVG. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `file_name` равно None или пустой. |

### См. также
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
