---
title: "Kelas Viewer"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili kelas utama yang mengontrol proses rendering dokumen."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

Mewakili kelas utama yang mengontrol proses rendering dokumen.

Tipe Viewer menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | Menginisialisasi [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | Menginisialisasi instance Viewer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | Menginisialisasi instance baru dari kelas [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | Menginisialisasi instance baru dari [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | Menginisialisasi instance Viewer baru. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | Melepaskan aliran file dan sumber daya internal yang dikelola. |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | Mengembalikan semua font yang digunakan dalam dokumen yang dimuat, termasuk font yang disematkan dan font sistem yang terpasang pada OS. |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | Mengembalikan lampiran yang terdapat dalam dokumen. |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | Mengembalikan informasi tentang file seperti jenis file dan bendera yang menunjukkan apakah file tersebut terenkripsi. |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | Mengembalikan tampilan dan informasi spesifik dokumen. |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | Menyimpan file lampiran ke aliran `destination`. |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | Melakukan pencarian teks dan menyorot teks yang ditemukan dalam dokumen yang dimuat sesuai dengan opsi yang diberikan. |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | Membuat tampilan semua halaman dokumen. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | Membuat tampilan halaman dokumen tertentu. |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | Membuat tampilan halaman dokumen tertentu. |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# Render DOCX ke HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# Render PDF ke PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
Panduan tugas yang menggunakan `Viewer`:

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### Lihat Juga
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
