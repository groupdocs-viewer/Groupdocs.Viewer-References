---
title: "ArchiveOptions Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Enthält Optionen zum Rendern der Archivdateien."
type: docs
url: /de/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Enthält Optionen zum Rendern der Archivdateien.

Der Typ ArchiveOptions stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Initialisiert eine Instanz der [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) Klasse. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Der angezeigte Archivdateiname. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Der zu rendernde Ordner. |

### Beispiel

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

### Siehe auch
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
