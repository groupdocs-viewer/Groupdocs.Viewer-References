---
title: "metode for_rendering_by_height"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan tinggi."
type: docs
url: /id/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_height/
is_root: false
weight: 1010
---


## for_rendering_by_height {#height}

Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan tinggi.

Untuk contoh kode, lihat dokumentasi.

```python
def for_rendering_by_height(cls, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| height | `int` | Tinggi hasil output (dalam piksel). |

**Returns:** CadOptions: New instance configured for rendering by height.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Ketika `height` kurang dari atau sama dengan nol. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def render_by_height():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("output_by_height.png")
        png_options.cad_options = CadOptions.for_rendering_by_height(1500)
        viewer.view(png_options)
```

### Lihat Juga
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
