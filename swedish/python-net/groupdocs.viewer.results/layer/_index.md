---
title: "Layer-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar ett lager som finns i CAD-ritningen."
type: docs
url: /sv/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Representerar ett lager som finns i CAD-ritningen.

Layer-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Initierar en ny instans av [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) klassen. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Initierar en ny Layer-instans. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Initierar en ny Layer-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Bestämmer om den aktuella Layer är densamma som det angivna Layer-objektet. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Kontrollerar om den aktuella [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) är lika med det angivna objektet. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Returnerar hashkoden för det aktuella Layer-objektet. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Returnerar en sträng som representerar det aktuella objektet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Namnet på lagret. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Lagrets synlighetsindikator. |

### Exempel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
