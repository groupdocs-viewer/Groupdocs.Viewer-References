---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Viewer untuk Python via .NET"
description: "Menginisialisasi sebuah instance dari kelas Tile."
type: docs
url: /id/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Menginisialisasi sebuah instance dari kelas [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/).

Untuk detail, lihat dokumentasi.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| start_point_x | `int` | Koordinat X dari titik kiri terendah pada gambar tempat tile dimulai. |
| start_point_y | `int` | Koordinat Y dari titik kiri terendah pada gambar tempat tile dimulai. |
| width | `int` | Lebar tile dalam piksel. |
| height | `int` | Tinggi tile dalam piksel. |

### Contoh

```python
from groupdocs.viewer.options import Tile

# Tentukan parameter tile
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Buat tile yang mewakili sebagian gambar
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Lihat Juga
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
