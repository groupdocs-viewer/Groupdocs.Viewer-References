---
title: "Metode from_rgb"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Membuat nilai Argb32Color dari saluran Merah, Hijau, Biru yang ditentukan, dengan saluran Alpha diatur menjadi sepenuhnya opak."
type: docs
url: /id/python-net/groupdocs.viewer.drawing/argb32color/from_rgb/
is_root: false
weight: 1090
---


## from_rgb {#red-green-blue}

Membuat nilai Argb32Color dari saluran Merah, Hijau, Biru yang ditentukan, dengan saluran Alpha diatur menjadi sepenuhnya opak.

```python
def from_rgb(cls, red, green, blue):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| red | `int` | Nilai saluran merah. |
| green | `int` | Nilai saluran hijau. |
| blue | `int` | Nilai saluran biru. |

**Returns:** Argb32Color: New Argb32Color value.

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.drawing import Argb32Color

with Viewer("sample.dwg") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.cad_options.background_color = Argb32Color.from_rgb(255, 255, 0)  # yellow
    viewer.view(view_options)
```

### Lihat Juga
* class [`Argb32Color`](/viewer/python-net/groupdocs.viewer.drawing/argb32color/)
