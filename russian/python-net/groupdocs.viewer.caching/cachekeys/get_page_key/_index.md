---
title: "get_page_key метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает уникальный идентификатор для кэш‑записи, представляющей файл страницы."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Возвращает уникальный идентификатор для кэш‑записи, представляющей файл страницы.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |
| extension | `str` | Суффикс имени файла (включая точку ".") например ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `extension` равно None или пустой. |

### См. также
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
