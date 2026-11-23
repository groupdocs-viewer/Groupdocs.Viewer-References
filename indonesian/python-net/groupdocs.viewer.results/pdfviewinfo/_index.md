---
title: "Kelas PdfViewInfo"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili informasi tampilan untuk dokumen PDF."
type: docs
url: /id/python-net/groupdocs.viewer.results/pdfviewinfo/
is_root: false
weight: 140
---


## PdfViewInfo class

Mewakili informasi tampilan untuk dokumen PDF.

Tipe PdfViewInfo menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/) | Menginisialisasi sebuah instance baru PdfViewInfo. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/#file_type-pages-printing_allowed) | Menginisialisasi sebuah instance baru PdfViewInfo. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Mengembalikan string yang mewakili objek saat ini. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [printing_allowed](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/printing_allowed/) | Properti printing_allowed menunjukkan apakah pencetakan dokumen diizinkan. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Tipe file. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Daftar halaman yang akan ditampilkan. (diturunkan dari [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Contoh

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import PdfViewInfo

def get_pdf_info():
    with Viewer("sample.pdf") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        pdf_info = cast(PdfViewInfo, info)

        print("File type:", pdf_info.file_type)
        print("Pages count:", len(pdf_info.pages))
        print("Printing allowed:", pdf_info.printing_allowed)

if __name__ == "__main__":
    get_pdf_info()
```

### Guides
Panduan tugas yang menggunakan `PdfViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
