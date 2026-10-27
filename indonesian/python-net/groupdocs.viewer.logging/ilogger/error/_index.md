---
title: "Metode error"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menulis pesan error."
type: docs
url: /id/python-net/groupdocs.viewer.logging/ilogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Menulis pesan error.

Pesan log error menyediakan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.

```python
def error(self, message, exception):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| message | `str` | Pesan error. |
| exception | `Exception` | Pengecualian. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Saat `exception` bernilai None. |

### Lihat Juga
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
