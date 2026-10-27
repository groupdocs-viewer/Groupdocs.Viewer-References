---
title: "Kelas OutlookViewInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili informasi tampilan untuk file Data Outlook."
type: docs
url: /id/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Mewakili informasi tampilan untuk file Data Outlook.

Tipe OutlookViewInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Menginisialisasi sebuah instance baru dari [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Menginisialisasi sebuah instance OutlookViewInfo baru. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Mengembalikan string yang mewakili objek saat ini. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Daftar folder yang terdapat dalam file data Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Tipe file. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Daftar halaman yang akan ditampilkan. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Contoh

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
Panduan tugas yang menggunakan `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
