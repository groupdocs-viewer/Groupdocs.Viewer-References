---
title: "Classe ProjectManagementViewInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les informations de vue pour un document MS Project."
type: docs
url: /fr/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Représente les informations de vue pour un document MS Project.

Le type ProjectManagementViewInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Initialise une nouvelle instance de [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Initialise une nouvelle instance de ProjectManagementViewInfo. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Renvoie une chaîne qui représente l'objet actuel. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | La date et l'heure auxquelles le projet doit être terminé. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | La date et l'heure à partir desquelles le projet a commencé. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Le type du fichier. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La liste des pages à afficher. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exemple

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
Guides de tâches qui utilisent `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
