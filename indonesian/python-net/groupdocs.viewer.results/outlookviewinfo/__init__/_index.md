---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari OutlookViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru dari [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Menginisialisasi sebuah instance OutlookViewInfo baru.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| folders | `List[str]` | Daftar folder yang terdapat dalam file Outlook Data. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilemparkan ketika `folders` bernilai None. |

### Lihat Juga
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
