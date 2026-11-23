---
title: "metode rotate_page"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menerapkan rotasi searah jarum jam pada halaman."
type: docs
url: /id/python-net/groupdocs.viewer.options/viewoptions/rotate_page/
is_root: false
weight: 1010
---


## rotate_page {#page_number-rotation}

Menerapkan rotasi searah jarum jam pada halaman.

Untuk detail, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/.

```python
def rotate_page(self, page_number, rotation):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_number | `int` | Nomor halaman, harus lebih besar dari 0 secara ketat. |
| rotation | `Rotation` | Nilai rotasi. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika rotasi untuk halaman dengan nomor `page_number` sudah ditambahkan. |

### Lihat Juga
* class [`ViewOptions`](/viewer/python-net/groupdocs.viewer.options/viewoptions/)
