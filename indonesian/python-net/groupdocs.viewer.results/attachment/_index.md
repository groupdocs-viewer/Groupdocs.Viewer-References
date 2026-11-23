---
title: "Kelas Attachment"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili file lampiran yang terdapat dalam pesan email, arsip, dokumen PDF, atau file data Outlook."
type: docs
url: /id/python-net/groupdocs.viewer.results/attachment/
is_root: false
weight: 20
---


## Attachment class

Mewakili file lampiran yang terdapat dalam pesan email, arsip, dokumen PDF, atau file data Outlook.

Tipe Attachment menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/) | Menginisialisasi sebuah instance baru dari [`Attachment`](/viewer/python-net/groupdocs.viewer.results/attachment/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#file_name-file_path) | Menginisialisasi sebuah instance Attachment baru. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-size) | Menginisialisasi sebuah instance baru dari kelas Attachment. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/attachment/__init__/#id-file_name-file_path-file_type-size) | Menginisialisasi sebuah instance baru dari kelas Attachment. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/attachment/to_string/) | Mengembalikan string yang merepresentasikan objek saat ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.results/attachment/file_name/) | Nama file lampiran. |
| [file_path](/viewer/python-net/groupdocs.viewer.results/attachment/file_path/) | Path relatif lampiran, misalnya `folder/file.docx`, atau nama file ketika file berada di root arsip, dalam pesan e‑mail, atau file data. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/attachment/file_type/) | Tipe file lampiran. |
| [id](/viewer/python-net/groupdocs.viewer.results/attachment/id/) | Pengidentifikasi unik lampiran dalam konteks satu file yang berisi lampiran ini. |
| [size](/viewer/python-net/groupdocs.viewer.results/attachment/size/) | Ukuran file lampiran dalam byte. |

### Contoh

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Akses properti lampiran, misalnya nama file
        print(attachment.file_name)
        # Simpan lampiran ke jalur file
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
