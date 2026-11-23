---
title: "Kelas Tile"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Mewakili wilayah gambar."
type: docs
url: /id/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Mewakili wilayah gambar.

Untuk detail, lihat dokumentasi di https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles.

Tipe Tile mengekspos anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Menginisialisasi sebuah instance dari kelas [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/). |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Mengembalikan koordinat X dari titik kanan tertinggi pada gambar tempat tile berakhir. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Mengembalikan koordinat Y dari titik kanan tertinggi pada gambar tempat tile berakhir. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Tinggi tile dalam piksel. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | Koordinat X dari titik kiri terendah pada gambar tempat tile dimulai. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Koordinat Y dari titik kiri terendah pada gambar tempat tile dimulai. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Lebar tile dalam piksel. |

### Contoh

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions, HtmlViewOptions, Tile

with Viewer("sample.dwg") as viewer:
    view_info = viewer.get_view_info(ViewInfoOptions.for_html_view())
    width = view_info.pages[0].width
    height = view_info.pages[0].height

    columns, rows = 2, 2
    tile_width = width / columns
    tile_height = height / rows

    view_options = HtmlViewOptions.for_embedded_resources(
        "output/drawing_tile_{0}.html"
    )
    for i in range(columns):
        for j in range(rows):
            tile = Tile(i * tile_width, j * tile_height, tile_width, tile_height)
            view_options.cad_options.tiles.append(tile)
```

### Lihat Juga
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
