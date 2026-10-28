---
title: "метод get_file_key"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает уникальный идентификатор для кэш‑записи, представляющей файл."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Возвращает уникальный идентификатор для кэш‑записи, представляющей файл.

```python
def get_file_key(cls, extension):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| extension | `str` | Суффикс имени файла (включая точку ".") например ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `extension` равно None или пустой. |

### См. также
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
