---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari ProjectManagementViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Menginisialisasi sebuah instance baru dari ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| start_date | `datetime` | Tanggal dan waktu sejak proyek dimulai. |
| end_date | `datetime` | Tanggal dan waktu ketika proyek harus diselesaikan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `pages` bernilai None. |

### Lihat Juga
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
