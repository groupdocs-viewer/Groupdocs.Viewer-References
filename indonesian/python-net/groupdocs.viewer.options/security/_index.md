---
title: "Kelas Security"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Opsi keamanan dokumen PDF."
type: docs
url: /id/python-net/groupdocs.viewer.options/security/
is_root: false
weight: 260
---


## Security class

Opsi keamanan dokumen PDF.

Untuk detail, lihat dokumentasi.

Tipe Security menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/security/__init__/) | Menginisialisasi sebuah instance dari kelas [`Security`](/viewer/python-net/groupdocs.viewer.options/security/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [document_open_password](/viewer/python-net/groupdocs.viewer.options/security/document_open_password/) | Kata sandi yang diperlukan untuk membuka dokumen PDF. |
| [permissions](/viewer/python-net/groupdocs.viewer.options/security/permissions/) | Izin dokumen PDF seperti pencetakan, modifikasi, dan ekstraksi data. |
| [permissions_password](/viewer/python-net/groupdocs.viewer.options/security/permissions_password/) | Kata sandi yang diperlukan untuk mengubah pengaturan izin. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, Security, Permissions

with Viewer("sample.docx") as viewer:
    security = Security()
    security.document_open_password = "o123"
    security.permissions_password = "p123"
    security.permissions = Permissions.ALLOW_ALL & ~Permissions.DENY_PRINTING

    pdf_options = PdfViewOptions("protected_document.pdf")
    pdf_options.security = security
    viewer.view(pdf_options)
```

### Guides
Panduan tugas yang menggunakan `Security`:

* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
