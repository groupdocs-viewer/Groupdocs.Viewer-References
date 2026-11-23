---
title: "get_resource_filter метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает строку фильтра для поиска записей кэша, представляющих объекты Resource."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Возвращает строку фильтра для поиска кэш‑записей, представляющих объекты [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Когда `page_number` меньше или равен нулю. |

### См. также
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
