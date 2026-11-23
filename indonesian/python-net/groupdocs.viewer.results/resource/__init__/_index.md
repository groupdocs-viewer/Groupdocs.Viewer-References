---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance Resource baru."
type: docs
url: /id/python-net/groupdocs.viewer.results/resource/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance Resource baru.

```python
def __init__(self):
    ...
```

## __init__ {#file_name-nested}

Menginisialisasi instance Resource baru.

```python
def __init__(self, file_name, nested):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Nama file sumber daya. |
| nested | `bool` | Menunjukkan apakah sumber daya berada di dalam sumber daya lain, misalnya sumber daya font yang berada di dalam sumber daya CSS atau SVG. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dikeluarkan ketika `file_name` bernilai None atau kosong. |

### Lihat Juga
* class [`Resource`](/viewer/python-net/groupdocs.viewer.results/resource/)
