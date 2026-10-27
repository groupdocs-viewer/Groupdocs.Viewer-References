---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari PdfViewOptions."
type: docs
url: /id/python-net/groupdocs.viewer.options/pdfviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_file_stream}

Menginisialisasi sebuah instance dari [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Untuk contoh kode, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/rendering-to-pdf/.

```python
def __init__(self, create_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data file output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `create_file_stream` adalah `None`. |

## __init__ {#create_file_stream-release_file_stream}

Menginisialisasi instance PdfViewOptions baru.

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, create_file_stream, release_file_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_file_stream | `CreateFileStream` | Callable yang mengembalikan aliran `io.RawIOBase` yang digunakan untuk menulis data file output. |
| release_file_stream | `ReleaseFileStream` | Callable yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke `create_file_stream`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `release_file_stream` adalah None. |

## __init__ {#file_stream_factory}

Menginisialisasi instance PdfViewOptions.

Untuk contoh kode, lihat dokumentasi: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

```python
def __init__(self, file_stream_factory):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_stream_factory | `IFileStreamFactory` | Factory yang mengimplementasikan metode untuk membuat dan melepaskan aliran file output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `file_stream_factory` adalah None. |

## __init__

Menginisialisasi instance PdfViewOptions.

Konstruktor ini menginisialisasi PdfViewOptions dengan `\"output.pdf\"` sebagai format jalur file untuk file output. File output akan ditempatkan di direktori kerja saat ini dari aplikasi.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

## __init__ {#output_file_path}

Menginisialisasi sebuah instance dari kelas [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, output_file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| output_file_path | `str` | Jalur untuk file PDF output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `output_file_path` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("spreadsheet.xlsx") as viewer:
    viewer.view(PdfViewOptions("output.pdf"))
```

### Lihat Juga
* class [`PdfViewOptions`](/viewer/python-net/groupdocs.viewer.options/pdfviewoptions/)
