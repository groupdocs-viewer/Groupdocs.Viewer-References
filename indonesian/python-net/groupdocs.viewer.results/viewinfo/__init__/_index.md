---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari ViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/viewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages}

Menginisialisasi sebuah instance ViewInfo baru.

```python
def __init__(self, file_type, pages):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `pages` bernilai None. |

### Lihat Juga
* class [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)
