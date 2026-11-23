---
title: "Klassen ArchiveOptions"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Innehåller alternativ för rendering av arkivfiler."
type: docs
url: /sv/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Innehåller alternativ för rendering av arkivfiler.

Typen ArchiveOptions exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Initierar en instans av klassen [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Det visade arkivfilnamnet. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Mappen som ska renderas. |

### Exempel

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

### Se även
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
