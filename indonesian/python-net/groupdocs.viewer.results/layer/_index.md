---
title: "Kelas Layer"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili lapisan yang terdapat dalam gambar CAD."
type: docs
url: /id/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Mewakili lapisan yang terdapat dalam gambar CAD.

Tipe Layer menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Menginisialisasi instance baru dari kelas [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Menginisialisasi instance Layer baru. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Menginisialisasi instance Layer baru. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Menentukan apakah Layer saat ini sama dengan objek Layer yang ditentukan. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Memeriksa apakah [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) saat ini sama dengan objek yang ditentukan. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Mengembalikan kode hash untuk objek Layer saat ini. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Mengembalikan string yang merepresentasikan objek saat ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Nama lapisan. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Indikator visibilitas lapisan. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Lihat Juga
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
