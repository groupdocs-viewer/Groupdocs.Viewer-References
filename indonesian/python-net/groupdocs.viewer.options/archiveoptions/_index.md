---
title: "Kelas ArchiveOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Berisi opsi untuk merender file arsip."
type: docs
url: /id/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Berisi opsi untuk merender file arsip.

Tipe ArchiveOptions menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Menginisialisasi sebuah instance kelas [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Nama file arsip yang ditampilkan. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Folder yang akan dirender. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
