---
title: "metode get_attachments"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mengembalikan lampiran yang terdapat dalam dokumen."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/get_attachments/
is_root: false
weight: 1030
---


## get_attachments

Mengembalikan lampiran yang terdapat dalam dokumen.

Pelajari lebih lanjut:
- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def get_attachments(self):
    ...
```

**Returns:** Attachments contained by the document.

| Mengecualikan | Deskripsi |
| :- | :- |
| `PasswordRequiredException` | Dilempar ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | Dilempar ketika kata sandi yang ditentukan tidak benar. |

### Contoh

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        # Simpan setiap lampiran ke sebuah file
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Lihat Juga
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
