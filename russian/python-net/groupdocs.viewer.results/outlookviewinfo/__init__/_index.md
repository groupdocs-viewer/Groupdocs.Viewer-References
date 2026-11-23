---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр OutlookViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Инициализирует новый экземпляр OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |
| folders | `List[str]` | Список папок, содержащихся в файле данных Outlook. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `folders` равно None. |

### См. также
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
