---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru PdfViewInfo."
type: docs
url: /id/python-net/groupdocs.viewer.results/pdfviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi sebuah instance baru PdfViewInfo.

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-printing_allowed}

Menginisialisasi sebuah instance baru PdfViewInfo.

```python
def __init__(self, file_type, pages, printing_allowed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_type | `FileType` | Tipe file. |
| pages | `List[Page]` | Daftar halaman yang akan ditampilkan. |
| printing_allowed | `bool` | Indikator izin pencetakan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `pages` bernilai None. |

### Lihat Juga
* class [`PdfViewInfo`](/viewer/python-net/groupdocs.viewer.results/pdfviewinfo/)
