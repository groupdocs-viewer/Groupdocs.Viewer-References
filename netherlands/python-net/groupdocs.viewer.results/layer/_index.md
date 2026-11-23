---
title: "Layer klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt een laag voor die in de CAD-tekening is opgenomen."
type: docs
url: /nl/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Stelt een laag voor die in de CAD-tekening is opgenomen.

Het Layer-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Initialiseert een nieuw exemplaar van de [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Initialiseert een nieuw Layer-exemplaar. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Initialiseert een nieuw Layer-exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Bepaalt of de huidige Layer hetzelfde is als het opgegeven Layer-object. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Controleert of de huidige [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) gelijk is aan het opgegeven object. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Retourneert de hashcode voor het huidige Layer-object. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | De naam van de laag. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | De zichtbaarheidsindicator van de laag. |

### Voorbeeld

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
