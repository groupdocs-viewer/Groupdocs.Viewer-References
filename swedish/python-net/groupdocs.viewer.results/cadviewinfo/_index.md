---
title: "CadViewInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar visningsinformation för en CAD-ritning."
type: docs
url: /sv/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Representerar visningsinformation för en CAD-ritning.

CadViewInfo-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Initierar en ny CadViewInfo-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returnerar en sträng som representerar det aktuella objektet. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | Listan över lager som ingår i CAD-ritningen. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | Listan över layouter som ingår i CAD-ritningen. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Filens typ. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Listan över sidor att visa. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exempel

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import CadViewInfo

def get_cad_info():
    with Viewer("sample.dwg") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        cad_info = cast(CadViewInfo, info)

        print("File type:", cad_info.file_type)
        print("Pages count:", len(cad_info.pages))
        print("Layers:")
        for layer in cad_info.layers:
            print(f"  {layer.name} (visible={layer.visible})")
        print("Layouts:")
        for layout in cad_info.layouts:
            print(f"  {layout.name} ({layout.width}x{layout.height})")

if __name__ == "__main__":
    get_cad_info()
```

### Guides
Uppgiftsguider som använder `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
