---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια παρουσία της κλάσης LoadOptions."
type: docs
url: /el/python-net/groupdocs.viewer.options/loadoptions/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια παρουσία της κλάσης [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type}

Αρχικοποιεί μια νέα παρουσία του LoadOptions.

Για παράδειγμα κώδικα, δείτε την τεκμηρίωση.

```python
def __init__(self, file_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου προς άνοιγμα. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εάν το `file_type` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer import Viewer, FileType
from groupdocs.viewer.options import LoadOptions, PdfViewOptions

load_options = LoadOptions(FileType.MD)  # specify the file type
with Viewer("terms_of_service.txt", load_options) as viewer:
    view_options = PdfViewOptions("output.pdf")
    viewer.view(view_options)
```

### Δείτε επίσης
* class [`LoadOptions`](/viewer/python-net/groupdocs.viewer.options/loadoptions/)
