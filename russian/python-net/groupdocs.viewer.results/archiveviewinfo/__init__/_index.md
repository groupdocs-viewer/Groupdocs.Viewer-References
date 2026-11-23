---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр ArchiveViewInfo."
type: docs
url: /ru/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Инициализирует новый экземпляр [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Инициализирует новый экземпляр ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_type | `FileType` | Тип файла. |
| pages | `List[Page]` | Список страниц для просмотра. |
| folders | `List[str]` | Список папок, содержащихся в архивном файле. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `folders` равен None. |

### См. также
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
