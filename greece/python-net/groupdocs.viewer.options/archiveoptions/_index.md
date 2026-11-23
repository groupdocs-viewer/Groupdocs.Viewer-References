---
title: "Κλάση ArchiveOptions"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Περιέχει επιλογές για την απόδοση των αρχείων αρχειοθέτησης."
type: docs
url: /el/python-net/groupdocs.viewer.options/archiveoptions/
is_root: false
weight: 10
---


## ArchiveOptions class

Περιέχει επιλογές για την απόδοση των αρχείων αρχειοθέτησης.

Ο τύπος ArchiveOptions εκθέτει τα παρακάτω μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/archiveoptions/__init__/) | Αρχικοποιεί ένα στιγμιότυπο της κλάσης [`ArchiveOptions`](/viewer/python-net/groupdocs.viewer.options/archiveoptions/). |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [file_name](/viewer/python-net/groupdocs.viewer.options/archiveoptions/file_name/) | Το εμφανιζόμενο όνομα αρχείου αποθήκης. |
| [folder](/viewer/python-net/groupdocs.viewer.options/archiveoptions/folder/) | Ο φάκελος που θα αποδοθεί. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions

with Viewer("documents.zip") as viewer:
    view_options = HtmlViewOptions.for_embedded_resources(
        "render_specific_archive_folder/specific_archive_folder.html"
    )
    view_options.archive_options.folder = "first_folder"
    viewer.view(view_options)
```

### Δείτε επίσης
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
