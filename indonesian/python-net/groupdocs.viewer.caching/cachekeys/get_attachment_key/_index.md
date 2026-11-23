---
title: "metode get_attachment_key"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file lampiran."
type: docs
url: /id/python-net/groupdocs.viewer.caching/cachekeys/get_attachment_key/
is_root: false
weight: 1010
---


## get_attachment_key {#attachment_id}

Mengembalikan pengidentifikasi unik untuk entri cache yang mewakili file lampiran.

```python
def get_attachment_key(cls, attachment_id):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attachment_id | `str` | Pengidentifikasi unik (dalam konteks satu berkas) dari lampiran. |

**Returns:** str: Unique identifier for the cache entry that represents attachment file.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilemparkan ketika `attachment_id` bernilai null atau kosong. |

### Lihat Juga
* class [`CacheKeys`](/viewer/python-net/groupdocs.viewer.caching/cachekeys/)
