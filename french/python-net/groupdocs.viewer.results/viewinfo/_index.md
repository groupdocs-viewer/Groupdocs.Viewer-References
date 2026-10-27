---
title: "Classe ViewInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les informations de vue pour un document générique."
type: docs
url: /fr/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Représente les informations de vue pour un document générique.

Le type ViewInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Initialise une nouvelle instance de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Initialise une nouvelle instance de ViewInfo. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Renvoie une chaîne qui représente l'objet actuel. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Le type du fichier. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La liste des pages à afficher. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
