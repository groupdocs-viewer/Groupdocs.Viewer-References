---
title: "ArchiveOptions klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Bevat opties voor het renderen van archiefbestanden."
type: docs
url: /nl/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Bevat opties voor het renderen van archiefbestanden.

Het type ArchiveOptions bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Initialiseert een instantie van de [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/) klasse. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | De weergegeven archiefbestandsnaam. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | De map die moet worden weergegeven. |

### Voorbeeld

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

### Zie ook
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
