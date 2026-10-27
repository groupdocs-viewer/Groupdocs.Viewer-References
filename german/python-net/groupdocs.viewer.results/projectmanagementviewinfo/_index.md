---
title: "Klasse ProjectManagementViewInfo"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Ansichtsinformationen für ein MS Project-Dokument dar."
type: docs
url: /de/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Stellt Ansichtsinformationen für ein MS Project-Dokument dar.

Der Typ ProjectManagementViewInfo stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Initialisiert eine neue Instanz von [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Initialisiert ein neues ProjectManagementViewInfo. |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Gibt eine Zeichenkette zurück, die das aktuelle Objekt darstellt. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | Das Datum und die Uhrzeit, zu der das Projekt abgeschlossen sein soll. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | Das Datum und die Uhrzeit, zu der das Projekt gestartet wurde. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Der Typ der Datei. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Die Liste der anzuzeigenden Seiten. (geerbt von [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Beispiel

```python
from typing import cast
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions
from groupdocs.viewer.results import ProjectManagementViewInfo

def get_project_info():
    with Viewer("sample.mpp") as viewer:
        info = viewer.get_view_info(ViewInfoOptions.for_html_view())
        project_info = cast(ProjectManagementViewInfo, info)

        print("File type:", project_info.file_type)
        print("Pages count:", len(project_info.pages))
        print("Start date:", project_info.start_date)
        print("End date:", project_info.end_date)

if __name__ == "__main__":
    get_project_info()
```

### Guides
Aufgabenleitfäden, die `ProjectManagementViewInfo` verwenden:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Siehe auch
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
