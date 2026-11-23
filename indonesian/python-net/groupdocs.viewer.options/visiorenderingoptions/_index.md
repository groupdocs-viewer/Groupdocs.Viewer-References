---
title: "Kelas VisioRenderingOptions"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili opsi untuk merender dokumen Visio."
type: docs
url: /id/python-net/groupdocs.viewer.options/visiorenderingoptions/
is_root: false
weight: 350
---


## VisioRenderingOptions class

Mewakili opsi untuk merender dokumen Visio.

Untuk detail, lihat dokumentasi.

Tipe VisioRenderingOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/__init__/) | Menginisialisasi sebuah instance dari kelas [`VisioRenderingOptions`](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [figure_width](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/figure_width/) | Lebar gambar; tinggi dihitung secara otomatis. Nilai default adalah 100. |
| [render_figures_only](/viewer/python-net/groupdocs.viewer.options/visiorenderingoptions/render_figures_only/) | Properti ini merender hanya gambar Visio, bukan diagram. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

def render_visio_shapes_only():
    # Muat dokumen Visio
    with Viewer("map.vsdx") as viewer:
        # Konversi file Visio ke PDF.
        view_options = PdfViewOptions("render_visio_shapes_only/visio_shapes_only.pdf")
        # Render hanya bentuk master.
        view_options.visio_rendering_options.render_figures_only = True
        # Tentukan lebar bentuk dalam piksel.
        view_options.visio_rendering_options.figure_width = 200
        viewer.view(view_options)

if __name__ == "__main__":
    render_visio_shapes_only()
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
