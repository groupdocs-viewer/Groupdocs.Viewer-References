---
title: "Metode error"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menulis pesan error ke konsol."
type: docs
url: /id/python-net/groupdocs.viewer.logging/filelogger/error/
is_root: false
weight: 1010
---


## error {#message-exception}

Menulis pesan error ke konsol. Pesan log error memberikan informasi tentang peristiwa yang tidak dapat dipulihkan dalam alur aplikasi.

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
* class [`FileLogger`](/viewer/python-net/groupdocs.viewer.logging/filelogger/)
