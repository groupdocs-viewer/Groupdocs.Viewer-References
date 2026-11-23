---
title: "metode save_attachment"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menyimpan berkas lampiran ke aliran tujuan."
type: docs
url: /id/python-net/groupdocs.viewer/viewer/save_attachment/
is_root: false
weight: 1070
---


## save_attachment {#attachment-destination}

Menyimpan file lampiran ke aliran `destination`.

- Learn more about getting document attachments in C#: https://docs.groupdocs.com/display/viewernet/Get+attachments
- Learn more about saving document attachments in C#: https://docs.groupdocs.com/display/viewernet/Save+attachments

```python
def save_attachment(self, attachment, destination):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attachment | `Attachment` | Lampiran. |
| destination | `io.RawIOBase` | Aliran yang dapat ditulis. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `destination` adalah None. |
| `PasswordRequiredException` | Ketika kata sandi diperlukan untuk membuka dokumen. |
| `IncorrectPasswordException` | Ketika kata sandi yang ditentukan tidak benar. |
| `GroupDocsViewerException` | Ketika lampiran tidak dapat ditemukan. |

### Contoh

```python
from groupdocs.viewer import Viewer

with Viewer("with_attachments.msg") as viewer:
    for attachment in viewer.get_attachments():
        viewer.save_attachment(attachment, f"./out/{attachment.file_name}")
```

### Lihat Juga
* class [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)
