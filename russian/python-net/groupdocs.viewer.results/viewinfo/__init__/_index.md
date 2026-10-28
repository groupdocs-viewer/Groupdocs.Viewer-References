---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр ViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Инициализирует новый экземпляр ViewInfo.

```python
def __init__(self, file_type, pages):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `pages` равно None. |

### См. также
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
