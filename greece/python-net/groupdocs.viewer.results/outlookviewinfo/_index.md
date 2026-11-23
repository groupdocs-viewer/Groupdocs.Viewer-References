---
title: "Κλάση OutlookViewInfo"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πληροφορίες προβολής για το αρχείο δεδομένων Outlook."
type: docs
url: /el/python-net/groupdocs.viewer.results/outlookviewinfo/
is_root: false
weight: 120
---


## OutlookViewInfo class

Αναπαριστά πληροφορίες προβολής για το αρχείο δεδομένων Outlook.

Ο τύπος OutlookViewInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/#file_type-pages-folders) | Αρχικοποιεί μια νέα παρουσία του OutlookViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [folders](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/folders/) | Η λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `OutlookViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
