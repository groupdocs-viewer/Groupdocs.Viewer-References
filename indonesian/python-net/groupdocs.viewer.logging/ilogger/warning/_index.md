---
title: "Metode warning"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menulis pesan peringatan."
type: docs
url: /id/python-net/groupdocs.viewer.logging/ilogger/warning/
is_root: false
weight: 1070
---


## warning {#message}

Menulis pesan peringatan.

Pesan log warning menyediakan informasi tentang peristiwa tak terduga dan dapat dipulihkan dalam alur aplikasi.

```python
def warning(self, message):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| message | `str` | Pesan peringatan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Saat `message` bernilai None. |

### Lihat Juga
* class [`ILogger`](/viewer/python-net/groupdocs.viewer.logging/ilogger/)
