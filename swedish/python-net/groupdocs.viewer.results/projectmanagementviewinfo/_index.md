---
title: "ProjectManagementViewInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar vyinformation för ett MS Project-dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Representerar vyinformation för ett MS Project-dokument.

ProjectManagementViewInfo-typen exponerar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Initierar en ny instans av [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Initierar en ny instans av ProjectManagementViewInfo. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returnerar en sträng som representerar det aktuella objektet. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | Datumet och tiden då projektet ska slutföras. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | Datumet och tiden då projektet startade. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Filens typ. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Listan över sidor att visa. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exempel

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
Uppgiftsguider som använder `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
