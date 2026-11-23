---
title: "Classe OutlookViewInfo"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta le informazioni di visualizzazione per il file di dati Outlook."
type: docs
url: /it/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Rappresenta le informazioni di visualizzazione per il file di dati Outlook.

Il tipo OutlookViewInfo espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Inizializza una nuova istanza di [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Inizializza una nuova istanza di OutlookViewInfo. |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | L'elenco delle cartelle contenute nel file dati Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Il tipo del file. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | L'elenco delle pagine da visualizzare. (eredita da [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Esempio

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
Guide operative che utilizzano `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Vedi anche
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
