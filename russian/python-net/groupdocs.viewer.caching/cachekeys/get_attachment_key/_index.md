---
title: "get_attachment_key метод"
second_title: "Справочник API GroupDocs.Viewer для Python через .NET"
description: "Возвращает уникальный идентификатор для кэш‑записи, представляющей файл вложения."
type: docs
url: /ru/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Возвращает уникальный идентификатор для кэш‑записи, представляющей файл вложения.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| attachment_id | `str` | Уникальный (в контексте одного файла) идентификатор вложения. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Исключения | Описание |
| :- | :- |
| `ValueError` | Выбрасывается, когда `attachment_id` равен null или пустой. |

### См. также
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
