---
title: "Classe CadViewInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les informations de vue d'un dessin CAO."
type: docs
url: /fr/python-net/groupdocs.viewer.results/cadviewinfo/
is_root: false
weight: 30
---


## CadViewInfo class

Représente les informations de vue d'un dessin CAO.

Le type CadViewInfo expose les membres suivants:

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/__init__/#file_type-pages-layers-layouts) | Initialise une nouvelle instance de CadViewInfo. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Renvoie une chaîne qui représente l'objet actuel. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [layers](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layers/) | La liste des calques contenue dans le dessin CAD. |
| [layouts](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/layouts/) | La liste des mises en page contenue dans le dessin CAD. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Le type du fichier. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La liste des pages à afficher. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exemple

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
Guides de tâches qui utilisent `CadViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
