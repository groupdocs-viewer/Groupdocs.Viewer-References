---
title: "Classe Layer"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente un calque contenu dans le dessin CAO."
type: docs
url: /fr/python-net/groupdocs.viewer.results/layer/
is_root: false
weight: 60
---


## Layer class

Représente un calque contenu dans le dessin CAO.

Le type Layer expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/) | Initialise une nouvelle instance de la classe [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name) | Initialise une nouvelle instance de Layer. |
| [__init__](/viewer/python-net/groupdocs.viewer.results/layer/__init__/#name-visible) | Initialise une nouvelle instance de Layer. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#other) | Détermine si le Layer actuel est le même que l'objet Layer spécifié. |
| [equals](/viewer/python-net/groupdocs.viewer.results/layer/equals/#obj) | Vérifie si le [`Layer`](/viewer/python-net/groupdocs.viewer.results/layer/) actuel est égal à l'objet spécifié. |
| [equals_layer](/viewer/python-net/groupdocs.viewer.results/layer/equals_layer/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.results/layer/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.results/layer/get_hash_code/) | Renvoie le code de hachage de l'objet Layer actuel. |
| [to_string](/viewer/python-net/groupdocs.viewer.results/layer/to_string/) | Renvoie une chaîne qui représente l'objet actuel. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [name](/viewer/python-net/groupdocs.viewer.results/layer/name/) | Le nom du layer. |
| [visible](/viewer/python-net/groupdocs.viewer.results/layer/visible/) | L'indicateur de visibilité du layer. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions
from groupdocs.viewer.results import Layer

with Viewer("sample.dwg") as viewer:
    options = PdfViewOptions("output.pdf")
    options.cad_options.layers = [Layer("QUADRANT")]
    viewer.view(options)
```

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
