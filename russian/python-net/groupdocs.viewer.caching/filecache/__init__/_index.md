---
title: "__init__ конструктор"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Инициализирует новый экземпляр FileCache."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/filecache/__init__/
is_root: false
weight: 10
---


## __init__ {#cache_path}

Инициализирует новый экземпляр FileCache.

```python
def __init__(self, cache_path):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| cache_path | `str` | Относительный или абсолютный путь, где будет храниться кэш документов. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `cache_path` равно None. |

## __init__ {#cache_path-cache_sub_folder}

Инициализирует новый экземпляр класса FileCache.

```python
def __init__(self, cache_path, cache_sub_folder):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| cache_path | `str` | Относительный или абсолютный путь, где будет храниться кэш документов. |
| cache_sub_folder | `str` | Подпапка, которую следует добавить к `cache_path`. |

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `cache_sub_folder` равно None. |

### См. также
* class [`FileCache`](/viewer/python-net/groupdocs.viewer.caching/filecache/)
