---
title: "kelas ViewerSettings"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mendefinisikan pengaturan untuk menyesuaikan perilaku Viewer."
type: docs
url: /id/python-net/groupdocs.viewer/viewersettings/
is_root: false
weight: 110
---


## ViewerSettings class

Mendefinisikan pengaturan untuk menyesuaikan perilaku [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

Tipe ViewerSettings menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache-logger) | Menginisialisasi sebuah instance ViewerSettings baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#cache) | Menginisialisasi sebuah instance ViewerSettings baru. |
| [__init__](/viewer/python-net/groupdocs.viewer/viewersettings/__init__/#logger) | Menginisialisasi sebuah instance ViewerSettings baru. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [cache](/viewer/python-net/groupdocs.viewer/viewersettings/cache/) | Implementasi cache yang digunakan untuk menyimpan hasil rendering. |
| [logger](/viewer/python-net/groupdocs.viewer/viewersettings/logger/) | Implementasi logger yang digunakan untuk pencatatan (Error, Peringatan, Jejak). |

### Contoh

```python
from groupdocs.viewer import Viewer, ViewerSettings
from groupdocs.viewer.logging import ConsoleLogger
from groupdocs.viewer.options import HtmlViewOptions

viewer_settings = ViewerSettings(logger=ConsoleLogger())
with Viewer("./sample.docx", settings=viewer_settings) as viewer:
    html_options = HtmlViewOptions.for_embedded_resources(
        "example/page_{0}.html"
    )
    viewer.view(html_options)
```

### Lihat Juga
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
