---
title: "Kelas FileName"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Nama file."
type: docs
url: /id/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Nama file.

Tipe FileName menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Menginisialisasi sebuah instance dari kelas [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Mengembalikan string yang merepresentasikan objek saat ini. |

### Bidang
| Bidang | Deskripsi |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Nama file kosong. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Nama file sumber. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
