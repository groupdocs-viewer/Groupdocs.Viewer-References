---
title: "OutlookViewInfo klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt weergave-informatie voor Outlook-gegevensbestand voor."
type: docs
url: /nl/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Stelt weergave-informatie voor Outlook-gegevensbestand voor.

Het type OutlookViewInfo bevat de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Initialiseert een nieuw exemplaar van [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Initialiseert een nieuw OutlookViewInfo‑exemplaar. |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | De lijst met mappen die in het Outlook‑gegevensbestand zijn opgenomen. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Het type van het bestand. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | De lijst met pagina's om te bekijken. (geërfd van [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Voorbeeld

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
Taakgidsen die `OutlookViewInfo` gebruiken:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Zie ook
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
