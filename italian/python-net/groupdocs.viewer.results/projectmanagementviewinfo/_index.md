---
title: "Classe ProjectManagementViewInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le informazioni di visualizzazione per un documento MS Project."
type: docs
url: /it/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Rappresenta le informazioni di visualizzazione per un documento MS Project.

Il tipo ProjectManagementViewInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Inizializza una nuova istanza di [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Inizializza una nuova istanza di ProjectManagementViewInfo. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | La data e ora in cui il progetto deve essere completato. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | La data e ora da cui il progetto è iniziato. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Il tipo del file. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | L'elenco delle pagine da visualizzare. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Esempio

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
Guide operative che utilizzano `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
