---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas JpgViewOptions."
type: docs
url: /id/python-net/groupdocs.viewer.options/jpgviewoptions/__init__/
is_root: false
weight: 10
---


## __init__ {#create_page_stream}

Menginisialisasi sebuah instance dari kelas JpgViewOptions.

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

Menginisialisasi sebuah instance dari kelas JpgViewOptions.

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, create_page_stream, release_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Callable yang menginstansiasi stream yang digunakan untuk menulis data halaman output. |
| release_page_stream | `ReleasePageStream` | Callable yang melepaskan stream yang dibuat oleh metode yang ditetapkan ke delegate yang diteruskan ke `create_page_stream`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `release_page_stream` bernilai None. |

## __init__ {#page_stream_factory}

Menginisialisasi sebuah instance dari kelas [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Untuk contoh kode, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg.

```python
def __init__(self, page_stream_factory):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `page_stream_factory` bernilai None. |

## __init__

Menginisialisasi sebuah instance JpgViewOptions.

Konstruktor ini menginisialisasi sebuah instance dari [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/) dengan "p_{0}.jpg" sebagai format jalur file untuk file output. File output ditempatkan ke direktori kerja saat ini dari aplikasi.

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

with Viewer("invoice.xlsx") as viewer:
    view_options = JpgViewOptions("render_excel_to_jpg/excel_to_jpg_{0}.jpg")
    view_options.width = 800
    view_options.height = 900
    viewer.view(view_options)
```

## __init__ {#file_path_format}

Menginisialisasi sebuah instance baru dari [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def __init__(self, file_path_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path_format | `str` | Format jalur file, misalnya 'page_{0}.jpg'. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `file_path_format` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import JpgViewOptions

def render_to_jpg():
    # Muat dokumen (misalnya, file Excel)
    with Viewer("invoice.xlsx") as viewer:
        # Buat opsi tampilan JPEG dengan pola nama file.
        view_options = JpgViewOptions("output/excel_page_{0}.jpg")
        view_options.width = 800
        view_options.height = 900
        viewer.view(view_options)

if __name__ == "__main__":
    render_to_jpg()
```

### Lihat Juga
* class [`JpgViewOptions`](/viewer/python-net/groupdocs.viewer.options/jpgviewoptions/)
