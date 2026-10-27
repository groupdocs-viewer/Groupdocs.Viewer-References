---
title: "Kelas LoadOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Opsi yang digunakan untuk membuka file."
type: docs
url: /id/python-net/groupdocs.viewer.options/loadoptions/
is_root: false
weight: 110
---


## LoadOptions class

Opsi yang digunakan untuk membuka file.

Tipe LoadOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/) | Menginisialisasi sebuah instance dari kelas [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/). |
| [__init__](/viewer/python-net/groupdocs.viewer.options/loadoptions/__init__/#file_type) | Menginisialisasi instance LoadOptions baru. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [detect_encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/detect_encoding/) | Properti ini memungkinkan deteksi pengkodean untuk file [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), [`FileType.csv`](/viewer/python-net/groupdocs.viewer.filetype/csv/), dan [`FileType.tsv`](/viewer/python-net/groupdocs.viewer.filetype/tsv/). |
| [encoding](/viewer/python-net/groupdocs.viewer.options/loadoptions/encoding/) | Pengkodean yang digunakan saat membuka file berbasis teks atau pesan email seperti [`FileType.csv`](/viewer/python-net/groupdocs.viewer/filetype/csv/), [`FileType.txt`](/viewer/python-net/groupdocs.viewer/filetype/txt/), dan [`FileType.msg`](/viewer/python-net/groupdocs.viewer/filetype/msg/). Nilai default adalah `utf-8`. |
| [file_type](/viewer/python-net/groupdocs.viewer.options/loadoptions/file_type/) | Tipe file yang akan dibuka. |
| [password](/viewer/python-net/groupdocs.viewer.options/loadoptions/password/) | Kata sandi untuk membuka file terenkripsi. |
| [resource_loading_timeout](/viewer/python-net/groupdocs.viewer.options/loadoptions/resource_loading_timeout/) | Batas waktu untuk memuat sumber daya eksternal. |
| [skip_external_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) | Properti ini menonaktifkan pemuatan semua sumber daya eksternal seperti gambar, kecuali yang terdaftar dalam [`LoadOptions.whitelisted_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/). |
| [try_repair](/viewer/python-net/groupdocs.viewer.options/loadoptions/try_repair/) | Properti ini memungkinkan GroupDocs.Viewer untuk mencoba memperbaiki kerusakan struktural pada dokumen PDF. Nilai default adalah False. |
| [whitelisted_resources](/viewer/python-net/groupdocs.viewer.options/loadoptions/whitelisted_resources/) | Daftar fragmen URL yang sesuai dengan sumber daya eksternal yang harus dimuat ketika [`LoadOptions.skip_external_resources`](/viewer/python-net/groupdocs.viewer.options/loadoptions/skip_external_resources/) disetel ke `True`. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, LoadOptions

load_options = LoadOptions()
load_options.password = "12345"

with Viewer("protected.docx", load_options) as viewer:
    viewer.view(HtmlViewOptions.for_embedded_resources("page_{0}.html"))
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
