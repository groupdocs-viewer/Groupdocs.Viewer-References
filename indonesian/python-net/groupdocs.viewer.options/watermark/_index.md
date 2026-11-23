---
title: "Kelas Watermark"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili watermark teks."
type: docs
url: /id/python-net/groupdocs.viewer.options/watermark/
is_root: false
weight: 360
---


## Watermark class

Mewakili watermark teks.

Lihat dokumentasi online untuk informasi lebih lanjut.

Tipe Watermark menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/watermark/__init__/#text) | Menginisialisasi sebuah instance dari kelas [`Watermark`](/viewer/python-net/groupdocs.viewer.options/watermark/). |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [color](/viewer/python-net/groupdocs.viewer.options/watermark/color/) | Warna watermark. Nilai default adalah `Rgb24Color.known_colors.css_level1.red`. |
| [font_name](/viewer/python-net/groupdocs.viewer.options/watermark/font_name/) | Nama font yang digunakan untuk watermark. |
| [position](/viewer/python-net/groupdocs.viewer.options/watermark/position/) | Posisi watermark. Nilai default adalah `Position.diagonal`. |
| [size](/viewer/python-net/groupdocs.viewer.options/watermark/size/) | Ukuran watermark. Nilai default adalah [`Size.full_size`](/viewer/python-net/groupdocs.viewer.options/size/full_size/). |
| [text](/viewer/python-net/groupdocs.viewer.options/watermark/text/) | Teks watermark. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, Watermark

def add_text_watermark():
    # Muat dokumen
    with Viewer("sample.docx") as viewer:
        # Buat file HTML.
        viewOptions = HtmlViewOptions.for_embedded_resources(
            "add_text_watermark/output-watermark.html"
        )
        # Tambahkan watermark.
        viewOptions.watermark = Watermark("This is a watermark")
        viewer.view(viewOptions)

if __name__ == "__main__":
    add_text_watermark()
```

### Guides
Panduan tugas yang menggunakan `Watermark`:

* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
