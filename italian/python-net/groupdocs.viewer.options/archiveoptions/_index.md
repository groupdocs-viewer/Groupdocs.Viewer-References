---
title: "Classe ArchiveOptions"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Contiene le opzioni per il rendering dei file di archivio."
type: docs
url: /it/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Contiene le opzioni per il rendering dei file di archivio.

Il tipo ArchiveOptions espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Inizializza un'istanza della classe [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Il nome del file di archivio visualizzato. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | La cartella da renderizzare. |

### Esempio

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

### Vedi anche
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
