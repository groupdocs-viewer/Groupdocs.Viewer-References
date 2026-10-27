---
title: "metode get_resource_filter"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan string filter untuk mencari entri cache yang mewakili objek Resource."
type: docs
url: /id/python-net/groupdocs.viewer.caching/cachekeys/get_resource_filter/
is_root: false
weight: 1060
---


## get_resource_filter {#page_number}

Mengembalikan string filter untuk mencari entri cache yang mewakili objek [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/).

```python
def get_resource_filter(cls, page_number):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Jumlah halaman. |

**Returns:** str: Filter string to search for cache entries that represent `Resource` objects.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `page_number` kurang atau sama dengan nol. |

### Lihat Juga
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
