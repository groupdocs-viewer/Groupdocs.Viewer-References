---
title: "metode for_rendering_by_width"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas CadOptions untuk merender berdasarkan lebar."
type: docs
url: /id/python-net/groupdocs.viewer.options/cadoptions/for_rendering_by_width/
is_root: false
weight: 1030
---


## for_rendering_by_width {#width}

Menginisialisasi sebuah instance dari kelas [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/) untuk rendering berdasarkan lebar.

```python
def for_rendering_by_width(cls, width):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| width | `int` | Lebar hasil output (dalam piksel). |

**Returns:** CadOptions: New instance of the `CadOptions` class for rendering by width.

| Mengecualikan | Deskripsi |
| :- | :- |
| `ValueError` | Jika `width` kurang dari atau sama dengan nol. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, CadOptions

def enable_performance_mode():
    # Muat file CAD
    with Viewer("sample.dwg") as viewer:
        view_options = HtmlViewOptions.for_embedded_resources(
            "enable_performance_mode/Output-Page#{0}.html"
        )
        view_options.cad_options = CadOptions.for_rendering_by_width(1000)
        view_options.cad_options.enable_performance_conversion_mode = True
        viewer.view(view_options)

if __name__ == "__main__":
    enable_performance_mode()
```

### Lihat Juga
* class [`CadOptions`](/viewer/python-net/groupdocs.viewer.options/cadoptions/)
