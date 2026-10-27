---
title: "Classe ArchiveViewInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le informazioni di visualizzazione per un file di archivio."
type: docs
url: /it/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Rappresenta le informazioni di visualizzazione per un file di archivio.

Il tipo ArchiveViewInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Inizializza una nuova istanza di [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Inizializza una nuova istanza di ArchiveViewInfo. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Le cartelle contenute nel file archivio. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Il tipo del file. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | L'elenco delle pagine da visualizzare. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Esempio

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
Guide operative che utilizzano `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
