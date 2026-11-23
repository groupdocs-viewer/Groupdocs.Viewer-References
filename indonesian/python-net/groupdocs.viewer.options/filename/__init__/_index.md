---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas FileName."
type: docs
url: /id/python-net/groupdocs.viewer.options/filename/__init__/
is_root: false
weight: 10
---


## __init__ {#file_name}

Menginisialisasi sebuah instance dari kelas [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/).

```python
def __init__(self, file_name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_name | `str` | Nama file. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_name` bernilai None. |

### Contoh

```python
from groupdocs.viewer.options import FileName

# Buat instance FileName dengan nama arsip khusus
custom_name = FileName("Sample Files")
```

### Lihat Juga
* class [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/)
