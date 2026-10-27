---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi instance baru dari kelas Layer."
type: docs
url: /id/python-net/groupdocs.viewer.results/layer/__init__/
is_root: false
weight: 10
---


## __init__

Menginisialisasi instance baru dari kelas [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/).

```python
def __init__(self):
    ...
```

### Contoh

```python
from groupdocs.viewer.results import Layer

# Buat lapisan dengan nama yang ditentukan.
layer = Layer("QUADRANT")
```

## __init__ {#name}

Menginisialisasi instance Layer baru.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama lapisan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `name` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer.results import Layer

# Buat lapisan dengan nama yang ditentukan
layer = Layer("QUADRANT")
```

## __init__ {#name-visible}

Menginisialisasi instance Layer baru.

```python
def __init__(self, name, visible):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama lapisan. |
| visible | `bool` | Indikator visibilitas lapisan. |

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `name` bernilai None atau kosong. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("render_specific_layers/specific_layers.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Lihat Juga
* class [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/)
