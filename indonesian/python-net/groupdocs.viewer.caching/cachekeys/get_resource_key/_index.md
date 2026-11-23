---
title: "metode get_resource_key"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili objek Resource."
type: docs
url: /id/python-net/groupdocs.viewer.caching/cachekeys/get_resource_key/
is_root: false
weight: 1070
---


## get_resource_key {#page_number-resource}

Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili objek [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_key(cls, page_number, resource):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |
| resource | `Resource` | Sumber HTML. |

**Returns:** str: Unique identifier for the cache entry that represents `Resource` object.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `page_number` kurang dari atau sama dengan nol, atau jika `resource` bernilai None. |

### Lihat Juga
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
