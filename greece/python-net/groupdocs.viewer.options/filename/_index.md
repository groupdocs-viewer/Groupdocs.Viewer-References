---
title: "Κλάση FileName"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Το όνομα αρχείου."
type: docs
url: /el/python-net/groupdocs.viewer.options/filename/
is_root: false
weight: 60
---


## FileName class

Το όνομα αρχείου.

Ο τύπος FileName εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/filename/__init__/#file_name) | Αρχικοποιεί μια παρουσία της κλάσης [`FileName`](/viewer/python-net/groupdocs.viewer.options/filename/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [to_string](/viewer/python-net/groupdocs.viewer.options/filename/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Πεδία
| Πεδίο | Περιγραφή |
| :- | :- |
| [EMPTY](/viewer/python-net/groupdocs.viewer.options/filename/empty/) | Το κενό όνομα αρχείου. |
| [SOURCE](/viewer/python-net/groupdocs.viewer.options/filename/source/) | Το όνομα του αρχείου προέλευσης. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, FileName

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "output/archive_{0}.html"
    )
    view_options.archive_options.file_name = FileName("Sample Files")
    viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
