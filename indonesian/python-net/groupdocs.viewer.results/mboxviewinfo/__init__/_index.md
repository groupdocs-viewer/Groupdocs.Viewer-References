---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari MboxViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/mboxviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Menginisialisasi sebuah instance baru [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| notes_count | `int` | Jumlah catatan yang terdapat dalam file penyimpanan basis data Lotus. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `notes_count` bernilai None. |

### Lihat Juga
* class [`MboxViewInfo`](/viewer/python-net/groupdocs.viewer.results/mboxviewinfo/)
