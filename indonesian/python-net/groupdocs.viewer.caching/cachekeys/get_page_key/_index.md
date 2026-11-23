---
title: "metode get_page_key"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file halaman."
type: docs
url: /id/python-net/groupdocs.viewer.caching/cachekeys/get_page_key/
is_root: false
weight: 1050
---


## get_page_key {#page_number-extension}

Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file halaman.

```python
def get_page_key(cls, page_number, extension):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman. |
| extension | `str` | Akhiran nama file (termasuk titik ".") misalnya ".doc". |

**Returns:** str: Unique identifier for the cache entry that represents page file.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `extension` bernilai None atau kosong. |

### Lihat Juga
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
