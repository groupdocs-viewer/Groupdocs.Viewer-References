---
title: "Layer-Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt eine Ebene dar, die in der CAD-Zeichnung enthalten ist."
type: docs
url: /de/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Stellt eine Ebene dar, die in der CAD-Zeichnung enthalten ist.

Der Layer-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Initialisiert eine neue Instanz der [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) Klasse. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Initialisiert eine neue Layer-Instanz. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Initialisiert eine neue Layer-Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Bestimmt, ob das aktuelle Layer dem angegebenen Layer-Objekt entspricht. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Prüft, ob das aktuelle [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) dem angegebenen Objekt gleich ist. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Gibt den Hashcode für das aktuelle Layer-Objekt zurück. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Gibt einen String zurück, der das aktuelle Objekt repräsentiert. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Der Name des Layers. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | Der Sichtbarkeitsindikator des Layers. |

### Beispiel

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
