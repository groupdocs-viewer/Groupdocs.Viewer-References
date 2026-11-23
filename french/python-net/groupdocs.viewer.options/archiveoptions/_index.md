---
title: "Classe ArchiveOptions"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Contient les options pour le rendu des fichiers d’archive."
type: docs
url: /fr/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Contient les options pour le rendu des fichiers d’archive.

Le type ArchiveOptions expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Initialise une instance de la classe [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Propriétés
| Propriété | Description |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Le nom de fichier d'archive affiché. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Le dossier à rendre. |

### Exemple

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Voir aussi
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
