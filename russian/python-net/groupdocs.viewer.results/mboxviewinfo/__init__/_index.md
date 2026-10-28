---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр MboxViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Инициализирует новый [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/) экземпляр.

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |
| notes_count | `int` | Количество заметок, содержащихся в файле хранилища базы данных Lotus. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `notes_count` равно None. |

### См. также
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
