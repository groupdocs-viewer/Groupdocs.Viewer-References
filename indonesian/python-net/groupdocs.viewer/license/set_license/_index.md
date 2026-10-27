---
title: "metode set_license"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Terapkan lisensi ke proses saat ini."
type: docs
url: /id/python-net/groupdocs.viewer/license/set_license/
is_root: false
weight: 1010
---


## set_license {#license_source}

Terapkan lisensi ke proses saat ini.

```python
def set_license(self, license_source):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| license_source |  | Baik jalur string ke file ``.lic`` atau objek file‑like yang dapat dibaca yang menghasilkan byte lisensi. Input file‑like ditulis ke file sementara sebelum diteruskan ke bridge. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `TypeError` | Jika ``license_source`` bukan jalur string maupun objek file‑like yang dapat dibaca. |

### Lihat Juga
* class [`License`](/viewer/python-net/groupdocs.viewer/license/)
