---
title: "Metode for_external_resources"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas HtmlViewOptions untuk merender ke HTML dengan sumber daya eksternal."
type: docs
url: /id/python-net/groupdocs.viewer.options/htmlviewoptions/for_external_resources/
is_root: false
weight: 1060
---


## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/) untuk merender ke HTML dengan sumber daya eksternal.

Untuk contoh kode, lihat dokumentasi.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| create_resource_stream | `CreateResourceStream` | Metode yang melepaskan aliran yang dibuat oleh metode `create_page_stream`. |
| create_resource_url | `CreateResourceUrl` | Metode yang membuat URL untuk sumber daya HTML. |

**Returns:** New instance of the `HtmlViewOptions` class for rendering into HTML with external resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `create_resource_url` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("sample.docx") as viewer:
    options = HtmlViewOptions.for_external_resources(
        "page_{0}.html",
        "page_{0}/resource_{0}_{1}",
        "page_{0}/resource_{0}_{1}"
    )
    viewer.view(options)
```

## for_external_resources {#create_page_stream-create_resource_stream-create_resource_url-release_page_stream-release_resource_stream}

Menginisialisasi sebuah instance dari kelas HtmlViewOptions untuk merender ke HTML dengan sumber daya eksternal.

Untuk contoh penggunaan tambahan, lihat dokumentasi GroupDocs Viewer.

```python
def for_external_resources(cls, create_page_stream, create_resource_stream, create_resource_url, release_page_stream, release_resource_stream):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| create_page_stream | `CreatePageStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data halaman output. |
| create_resource_stream | `CreateResourceStream` | Metode yang menginstansiasi aliran yang digunakan untuk menulis data sumber daya HTML output. |
| create_resource_url | `CreateResourceUrl` | Metode yang membuat URL untuk sumber daya HTML. |
| release_page_stream | `ReleasePageStream` | Metode yang melepaskan aliran yang dibuat oleh delegasi yang diberikan ke `create_page_stream`. |
| release_resource_stream | `ReleaseResourceStream` | Metode yang melepaskan aliran yang dibuat oleh delegasi yang diberikan ke `create_resource_stream`. |

**Returns:** HtmlViewOptions: New instance of the HtmlViewOptions class for rendering into HTML with external resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `release_resource_stream` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_excel_to_html_external():
    # Muat spreadsheet Excel
    with Viewer("invoice.xlsx") as viewer:
        # Konversi spreadsheet ke HTML dengan sumber daya eksternal.
        # {0} dan {1} digantikan dengan nomor halaman saat ini dan nama sumber daya, masing-masing.
        view_options = HtmlViewOptions.for_external_resources(
            "render_excel_to_html_external/pdf_page_{0}.html",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}",
            "render_excel_to_html_external/pdf_page_{0}/resource_{0}_{1}"
        )
        viewer.view(view_options)

if __name__ == "__main__":
    render_excel_to_html_external()
```

## for_external_resources {#page_stream_factory-resource_stream_factory}

Menginisialisasi instance HtmlViewOptions untuk merender ke HTML dengan sumber daya eksternal.

Untuk detail lebih lanjut, lihat dokumentasi online.

```python
def for_external_resources(cls, page_stream_factory, resource_stream_factory):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| page_stream_factory | `IPageStreamFactory` | Fabrik yang mengimplementasikan metode untuk membuat dan melepaskan aliran halaman output. |
| resource_stream_factory | `IResourceStreamFactory` | Fabrik yang mengimplementasikan metode yang diperlukan untuk membuat URL sumber daya, menginstansiasi, dan melepaskan aliran sumber daya HTML output. |

**Returns:** HtmlViewOptions: A new HtmlViewOptions instance configured for external resources.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `resource_stream_factory` bernilai None. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Buat file HTML untuk setiap halaman dan simpan sumber daya eksternal secara terpisah.
    # {0} dan {1} digantikan dengan nomor halaman saat ini dan nama sumber daya, masing-masing.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

## for_external_resources

Menginisialisasi instance HtmlViewOptions yang dikonfigurasi untuk menghasilkan file HTML dengan sumber daya eksternal.

Instansi menggunakan string format yang disediakan:
- `html_file_path_format` – file path format for the output HTML files (e.g., `"page_{0}.html"`).
- `resources_path_format` – folder path format for external resource files (e.g., `"page_{0}/resource_{0}_{1}"`).
- `resources_url_format` – URL format for HTML resources (e.g., `"page_{0}/resource_{0}_{1}"`).

File output ditempatkan di direktori kerja saat ini dari aplikasi.

```python
def for_external_resources(cls):
    ...
```

**Returns:** HtmlViewOptions: Configured options for rendering HTML with external resources.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_docx_to_html_external():
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_docx_to_html_external()
```

## for_external_resources {#file_path_format-resource_file_path_format-resource_url_format}

Menginisialisasi sebuah instance dari kelas [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/).

Untuk contoh kode, lihat dokumentasi.

```python
def for_external_resources(cls, file_path_format, resource_file_path_format, resource_url_format):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path_format | `str` | Format jalur file, misalnya `'page_{0}.html'`. |
| resource_file_path_format | `str` | Format jalur file sumber daya, misalnya `'page_{0}/resource_{1}'`. |
| resource_url_format | `str` | Format URL sumber daya, misalnya `'page_{0}/resource_{1}'`. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `resource_url_format` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

def render_to_html_external():
    # Muat dokumen dan render setiap halaman ke file HTML dengan sumber daya eksternal.
    with Viewer("sample.docx") as viewer:
        html_options = HtmlViewOptions.for_external_resources(
            "page_{0}.html",
            "page_{0}/resource_{0}_{1}",
            "page_{0}/resource_{0}_{1}"
        )
        viewer.view(html_options)

if __name__ == "__main__":
    render_to_html_external()
```

### Lihat Juga
* class [`HtmlViewOptions`](/viewer/python-net/groupdocs.viewer.options/htmlviewoptions/)
