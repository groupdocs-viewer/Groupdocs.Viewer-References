---
title: "ProjectManagementViewInfo κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πληροφορίες προβολής για έγγραφο MS Project."
type: docs
url: /el/python-net/groupdocs.viewer.results/projectmanagementviewinfo/
is_root: false
weight: 150
---


## ProjectManagementViewInfo class

Αναπαριστά πληροφορίες προβολής για έγγραφο MS Project.

Ο τύπος ProjectManagementViewInfo εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/) | Δημιουργεί μια νέα παρουσία του [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/#file_type-pages-start_date-end_date) | Αρχικοποιεί ένα νέο στιγμιότυπο του ProjectManagementViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [end_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/end_date/) | Η ημερομηνία και ώρα κατά την οποία το έργο πρέπει να ολοκληρωθεί. |
| [start_date](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/start_date/) | Η ημερομηνία και ώρα από την οποία ξεκίνησε το έργο. |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. (κληρονομείται από [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/)) |

### Παράδειγμα

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
Οδηγοί εργασιών που χρησιμοποιούν `ProjectManagementViewInfo`:

* [Get Document Information](/viewer/python-net/guides/get-document-info/)

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
