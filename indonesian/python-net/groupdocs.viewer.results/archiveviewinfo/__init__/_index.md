---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari ArchiveViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Menginisialisasi instance ArchiveViewInfo baru.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| folders | `List[str]` | Daftar folder yang terdapat dalam file arsip. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `folders` bernilai None. |

### Lihat Juga
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
