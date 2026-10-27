---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas LoadOptions."
type: docs
url: /id/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance dari kelas [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Menginisialisasi instance LoadOptions baru.

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, file_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file yang akan dibuka. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_type` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Lihat Juga
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
