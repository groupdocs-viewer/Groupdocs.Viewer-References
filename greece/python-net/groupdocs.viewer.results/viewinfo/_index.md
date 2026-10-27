---
title: "ViewInfo κλάση"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά πληροφορίες προβολής για ένα γενικό έγγραφο."
type: docs
url: /el/python-net/groupdocs.viewer.results/viewinfo/
is_root: false
weight: 180
---


## ViewInfo class

Αναπαριστά πληροφορίες προβολής για ένα γενικό έγγραφο.

Ο τύπος ViewInfo εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/) | Αρχικοποιεί μια νέα παρουσία του [`ViewInfo`](/viewer/python-net/groupdocs.viewer.results/viewinfo/). |
| [__init__](/viewer/python-net/groupdocs.viewer.results/viewinfo/__init__/#file_type-pages) | Αρχικοποιεί μια νέα παρουσία ViewInfo. |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.results/viewinfo/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_type](/viewer/python-net/groupdocs.viewer.results/viewinfo/file_type/) | Ο τύπος του αρχείου. |
| [pages](/viewer/python-net/groupdocs.viewer.results/viewinfo/pages/) | Η λίστα των σελίδων προς προβολή. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import ViewInfoOptions

with Viewer("sample.docx") as viewer:
    options = ViewInfoOptions.for_html_view()
    view_info = viewer.get_view_info(options)
    for page in view_info.pages:
        print(f"Page {page.number}: {page.name}")
```

### Δείτε επίσης
* module [`groupdocs.viewer.results`](/viewer/python-net/groupdocs.viewer.results/)
