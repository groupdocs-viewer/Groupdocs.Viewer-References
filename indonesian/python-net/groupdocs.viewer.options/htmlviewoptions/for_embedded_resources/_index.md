---
title: "Metode for_embedded_resources"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance HtmlViewOptions untuk merender HTML dengan sumber daya yang disematkan."
type: docs
url: /id/python-net/groupdocs.viewer.options/htmlviewoptions/for_embedded_resources/
is_root: false
weight: 1010
---


## for_embedded_resources {#create_page_stream}

Menginisialisasi instance HtmlViewOptions untuk merender HTML dengan sumber daya yang disematkan.

Untuk detail lebih lanjut, lihat dokumentasi.

```python
def for_embedded_resources(cls, create_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |

**Returns:** HtmlViewOptions: New instance configured for rendering HTML with embedded resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `create_page_stream` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#create_page_stream-release_page_stream}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) untuk merender ke HTML dengan sumber daya yang disematkan.

```python
def for_embedded_resources(cls, create_page_stream, release_page_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| release_page_stream | `ReleasePageStream` | Metode yang melepaskan aliran yang dibuat oleh metode yang ditetapkan ke parameter `create_page_stream`. |

**Returns:** HtmlViewOptions: New instance of the `HtmlViewOptions` class for rendering into HTML with embedded resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `release_page_stream` bernilai `None`. Untuk contoh kode, lihat dokumentasi. |

## for_embedded_resources {#page_stream_factory}

Menginisialisasi instance HtmlViewOptions untuk merender ke HTML dengan sumber daya yang disematkan.

Untuk contoh kode, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources.

```python
def for_embedded_resources(cls, page_stream_factory):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |

**Returns:** HtmlViewOptions: New instance of HtmlViewOptions for rendering into HTML with embedded resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika page_stream_factory bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) dengan sumber daya yang disematkan.

Untuk contoh kode, lihat dokumentasi.

```python
def for_embedded_resources(cls):
    ...
```

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

## for_embedded_resources {#file_path_format}

Menginisialisasi instance HtmlViewOptions untuk sumber daya yang disematkan.

Untuk contoh kode, lihat dokumentasi.

```python
def for_embedded_resources(cls, file_path_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path_format | `str` | Format jalur file misalnya 'page_{0}.html'. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `file_path_format` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("document.docx") as viewer:
    options = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(options)
```

### Lihat Juga
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
