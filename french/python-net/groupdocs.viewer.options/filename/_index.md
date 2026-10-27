---
title: "Classe FileName"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Le nom de fichier."
type: docs
url: /fr/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Le nom de fichier.

Le type FileName expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Initialise une instance de la classe [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Renvoie une chaîne qui représente l'objet actuel. |

### Champs
| Champ | Description |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Le nom de fichier vide. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Le nom du fichier source. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
