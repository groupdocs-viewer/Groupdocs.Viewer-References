---
title: "get_resource_key метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает уникальный идентификатор записи кэша, представляющей объект Resource."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Возвращает уникальный идентификатор для кэш‑записи, представляющей объект [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| page_number | `int` | Номер страницы. |
| resource | `Resource` | HTML-ресурс. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Если `page_number` меньше или равен нулю, или если `resource` равно None. |

### См. также
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
