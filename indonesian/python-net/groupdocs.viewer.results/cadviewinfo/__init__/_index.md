---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru CadViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Menginisialisasi sebuah instance baru CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| layers | `List[Layer]` | Daftar lapisan yang terdapat dalam gambar CAD. |
| layouts | `List[Layout]` | Daftar lapisan yang terdapat dalam gambar CAD. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dikeluarkan ketika `layouts` bernilai None. |

### Lihat Juga
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
