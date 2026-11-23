---
title: "metode get_file_key"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file."
type: docs
url: /id/python-net/groupdocs.viewer.caching/cachekeys/get_file_key/
is_root: false
weight: 1040
---


## get_file_key {#extension}

Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file.

```python
def get_file_key(cls, extension):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extension | `str` | Akhiran nama file (termasuk titik ".") misalnya ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents file.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `extension` bernilai None atau kosong. |

### Lihat Juga
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
