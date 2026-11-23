---
title: "ProjectManagementViewInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt weergave-informatie voor een MS Project-document voor."
type: docs
url: /nl/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Stelt weergave-informatie voor een MS Project-document voor.

Het ProjectManagementViewInfo-type geeft de volgende leden weer:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Initialiseert een nieuw exemplaar van [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Initialiseert een nieuw exemplaar van ProjectManagementViewInfo. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | De datum en tijd waarop het project voltooid moet worden. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | De datum en tijd waarop het project is gestart. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Het type van het bestand. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | De lijst met pagina's om te bekijken. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Voorbeeld

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
Taakgidsen die `ProjectManagementViewInfo` gebruiken:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
