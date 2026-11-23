---
title: "Tile sınıfı"
second_title: "GroupDocs.Viewer Python için .NET üzerinden API Referansları"
description: "Çizim bölgesini temsil eder."
type: docs
url: /tr/python-net/groupdocs.viewer.options/tile/
is_root: false
weight: 310
---


## Tile class

Çizim bölgesini temsil eder.

Ayrıntılar için https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#split-a-drawing-into-tiles adresindeki belgeleri inceleyin.

Tile türü aşağıdaki üyeleri sunar:

### Yapıcılar
| Yapıcı | Açıklama |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/tile/__init__/#start_point_x-start_point_y-width-height) | Bir [`Tile`](/viewer/python-net/groupdocs.viewer.options/tile/) sınıfının bir örneğini başlatır. |

### Yöntemler
| Yöntem | Açıklama |
| :- | :- |
| [get_end_point_x](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_x/) | Döşemenin bittiği çizimdeki en yüksek sağ noktanın X koordinatını döndürür. |
| [get_end_point_y](/viewer/python-net/groupdocs.viewer.options/tile/get_end_point_y/) | Döşemenin bittiği çizimdeki en yüksek sağ noktanın Y koordinatını döndürür. |

### Özellikler
| Özellik | Açıklama |
| :- | :- |
| [height](/viewer/python-net/groupdocs.viewer.options/tile/height/) | Döşemenin piksel cinsinden yüksekliği. |
| [start_point_x](/viewer/python-net/groupdocs.viewer.options/tile/start_point_x/) | Döşemenin başladığı çizimdeki en düşük sol noktanın X koordinatı. |
| [start_point_y](/viewer/python-net/groupdocs.viewer.options/tile/start_point_y/) | Döşemenin başladığı çizimdeki en düşük sol noktanın Y koordinatı. |
| [width](/viewer/python-net/groupdocs.viewer.options/tile/width/) | Döşemenin piksel cinsinden genişliği. |

### Örnek

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

### Ayrıca Bakınız
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
