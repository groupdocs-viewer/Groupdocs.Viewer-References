---
title: "OutlookViewInfo Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Ansichtsinformationen für Outlook-Datendateien dar."
type: docs
url: /de/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Stellt Ansichtsinformationen für Outlook-Datendateien dar.

Der OutlookViewInfo-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Initialisiert eine neue Instanz von [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Initialisiert eine neue OutlookViewInfo-Instanz. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Die Liste der im Outlook-Datendatei enthaltenen Ordner. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Der Typ der Datei. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Die Liste der anzuzeigenden Seiten. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Beispiel

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import OutlookViewInfo

def get_outlook_info():
    with Viewer("sample.pst") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        outlook_info = cast(OutlookViewInfo, info)

        print("File type:", outlook_info.file_type)
        print("Pages count:", len(outlook_info.pages))
        print("Folders:")
        for folder in outlook_info.folders:
            print(f"  {folder}")

if __name__ == "__main__":
    get_outlook_info()
```

### Guides
Aufgabenleitfäden, die `OutlookViewInfo` verwenden:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
