---
title: "ArchiveViewInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar visningsinformation för en arkivfil."
type: docs
url: /sv/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Representerar visningsinformation för en arkivfil.

ArchiveViewInfo-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Initierar en ny instans av [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Initierar en ny ArchiveViewInfo-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returnerar en sträng som representerar det aktuella objektet. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Mapparna som finns i arkivfilen. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Filens typ. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Listan över sidor att visa. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exempel

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
Uppgiftsguider som använder `ArchiveViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
