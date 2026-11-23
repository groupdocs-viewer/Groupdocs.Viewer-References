---
title: "__init__ yapıcı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Tile sınıfının bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.viewer.options/tile/__init__/
is_root: false
weight: 10
---


## __init__ {#start_point_x-start_point_y-width-height}

Bir [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) sınıfının bir örneğini başlatır.

Ayrıntılar için belgelere bakın.

```python
def __init__(self, start_point_x, start_point_y, width, height):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| start_point_x | `int` | Döşemenin başladığı çizimdeki en düşük sol noktanın X koordinatı. |
| start_point_y | `int` | Döşemenin başladığı çizimdeki en düşük sol noktanın Y koordinatı. |
| width | `int` | Döşemenin piksel cinsinden genişliği. |
| height | `int` | Döşemenin piksel cinsinden yüksekliği. |

### Örnek

```python
from groupdocs.viewer.options import Tile

# Tile parametrelerini tanımla
start_x = 0
start_y = 0
tile_width = 500
tile_height = 400

# Çizimin bir bölümünü temsil eden bir tile oluştur.
tile = Tile(start_x, start_y, tile_width, tile_height)
```

### Ayrıca Bakınız
* class [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/)
