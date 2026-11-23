---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance PngViewOptions baru."
type: docs
url: /id/python-net/groupdocs.viewer.options/pngviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Menginisialisasi sebuah instance baru [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, create_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `create_page_stream` bernilai None. |

## __init__ {#create_page_stream-release_page_stream}

Menginisialisasi sebuah instance dari kelas [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| release_page_stream | `ReleasePageStream` | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke delegasi yang diteruskan ke parameter `create_page_stream`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `release_page_stream` bernilai None. |

## __init__ {#page_stream_factory}

Menginisialisasi sebuah instance baru [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Untuk informasi lebih lanjut, lihat dokumentasi.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `page_stream_factory` bernilai `None`. |

## __init__

Menginisialisasi sebuah instance PngViewOptions.

Konstruktor ini membuat sebuah [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/) dengan ``"p_{0}.png"`` sebagai format jalur file default untuk file output. File PNG yang dihasilkan disimpan di direktori kerja saat ini dari aplikasi.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

## __init__ {#file_path_format}

Menginisialisasi sebuah instance baru [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path_format | `str` | Format jalur file, misalnya `'page_{0}.png'`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `file_path_format` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("document.pdf") as viewer:
    viewer.view(PngViewOptions("page_{0}.png"))
```

### Lihat Juga
* class [`PngViewOptions`](/viewer/python-net/groupdocs.viewer.options/pngviewoptions/)
