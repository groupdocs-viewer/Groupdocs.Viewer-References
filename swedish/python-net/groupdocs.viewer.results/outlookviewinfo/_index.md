---
title: "OutlookViewInfo-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar vyinformation för Outlook Data-fil."
type: docs
url: /sv/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Representerar vyinformation för Outlook Data-fil.

OutlookViewInfo-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Initierar en ny instans av [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Initierar en ny OutlookViewInfo-instans. |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Returnerar en sträng som representerar det aktuella objektet. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Listan över mappar som finns i Outlook-datafilen. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Filens typ. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Listan över sidor att visa. (ärvd från [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Exempel

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
Uppgiftsguider som använder `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Se även
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
