---
title: "ArchiveViewInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt weergave‑informatie voor een archiefbestand voor."
type: docs
url: /nl/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Stelt weergave‑informatie voor een archiefbestand voor.

Het ArchiveViewInfo-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Initialiseert een nieuw exemplaar van [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Initialiseert een nieuw ArchiveViewInfo-exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | De mappen die in het archiefbestand zitten. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Het type van het bestand. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | De lijst met pagina's om te bekijken. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Voorbeeld

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
Taakgidsen die `ArchiveViewInfo` gebruiken:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
