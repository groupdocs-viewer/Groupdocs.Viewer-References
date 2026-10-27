---
title: "metode for_rendering_by_scale_factor"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan faktor skala."
type: docs
url: /id/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_scale_factor/
is_root: false
weight: 1020
---


## for_rendering_by_scale_factor {#scale_factor}

Menginisialisasi sebuah instance CadOptions untuk rendering berdasarkan faktor skala.

Untuk contoh kode, lihat dokumentasi.

```python
def for_rendering_by_scale_factor(cls, scale_factor):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| scale_factor | `float` | Nilai yang lebih tinggi dari 1 memperbesar hasil output; nilai antara 0 dan 1 mengurangi hasil output. |

**Returns:** CadOptions: New instance of the CadOptions class for rendering by scale factor.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Dikeluarkan ketika `scale_factor` kurang dari atau sama dengan nol. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions, CadOptions

def set_image_size():
    with Viewer("sample.dwg") as viewer:
        png_options = PngViewOptions("set_image_size/image_with_size_limits.pdf")
        png_options.cad_options = CadOptions.for_rendering_by_scale_factor(0.5)
        viewer.view(png_options)

if __name__ == "__main__":
    set_image_size()
```

### Lihat Juga
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
