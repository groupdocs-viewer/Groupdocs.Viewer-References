---
title: "ArchiveViewInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Ansichtsinformationen für eine Archivdatei dar."
type: docs
url: /de/python-net/groupdocs.viewer.results/archiveviewinfo/
is_root: false
weight: 10
---


## ArchiveViewInfo class

Stellt Ansichtsinformationen für eine Archivdatei dar.

Der Typ ArchiveViewInfo stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/) | Initialisiert eine neue Instanz von [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/#file_type-pages-folders) | Initialisiert eine neue ArchiveViewInfo‑Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/folders/) | Die vom Archivdatei enthaltenen Ordner. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Der Typ der Datei. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Die Liste der anzuzeigenden Seiten. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Beispiel

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
Aufgabenleitfäden, die `ArchiveViewInfo` verwenden:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
