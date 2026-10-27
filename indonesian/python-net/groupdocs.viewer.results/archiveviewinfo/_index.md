---
title: "Kelas ArchiveViewInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili informasi tampilan untuk file arsip."
type: docs
url: /id/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Mewakili informasi tampilan untuk file arsip.

Tipe ArchiveViewInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Menginisialisasi instance baru dari [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Menginisialisasi instance ArchiveViewInfo baru. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Mengembalikan string yang mewakili objek saat ini. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Folder-folder yang terdapat dalam file arsip. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Tipe file. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Daftar halaman yang akan ditampilkan. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Contoh

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Panduan tugas yang menggunakan `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
