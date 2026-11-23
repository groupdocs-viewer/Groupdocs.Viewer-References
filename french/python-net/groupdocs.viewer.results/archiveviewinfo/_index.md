---
title: "Classe ArchiveViewInfo"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente les informations de vue d'un fichier d'archive."
type: docs
url: /fr/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Représente les informations de vue d'un fichier d'archive.

Le type ArchiveViewInfo expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Initialise une nouvelle instance de [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Initialise une nouvelle instance d'ArchiveViewInfo. |

### Méthodes
| Méthode | Description |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Renvoie une chaîne qui représente l'objet actuel. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Propriétés
| Propriété | Description |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Les dossiers contenus dans le fichier d'archive. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Le type du fichier. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | La liste des pages à afficher. (hérité de [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exemple

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ArchiveViewInfo

def get_archive_info():
    with Viewer("documents.zip") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        archive_info = cast(ArchiveViewInfo, info)

        print("File type:", archive_info.file_type)
        print("Pages count:", len(archive_info.pages))
        print("Folders:")
        for folder in archive_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_archive_info()
```

### Guides
Guides de tâches qui utilisent `ArchiveViewInfo` :

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Voir aussi
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
