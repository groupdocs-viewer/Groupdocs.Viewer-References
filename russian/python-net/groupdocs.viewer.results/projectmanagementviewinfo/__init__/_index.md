---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр ProjectManagementViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Инициализирует новый экземпляр ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |
| start_date | `datetime` | Дата и время, с которых проект начался. |
| end_date | `datetime` | Дата и время, когда проект должен быть завершён. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `pages` равно None. |

### См. также
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
