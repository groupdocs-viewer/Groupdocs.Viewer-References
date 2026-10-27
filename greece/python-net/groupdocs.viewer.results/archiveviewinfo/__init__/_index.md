---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία της κλάσης ArchiveViewInfo."
type: docs
url: /el/python-net/groupdocs.viewer.results/archiveviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο αντικείμενο του [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Αρχικοποιεί ένα νέο αντικείμενο ArchiveViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου. |
| pages | `List[Page]` | Η λίστα των σελίδων προς προβολή. |
| folders | `List[str]` | Η λίστα των φακέλων που περιέχονται στο αρχείο αρχειοθήκης. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν το `folders` είναι None. |

### Δείτε επίσης
* class [`ArchiveViewInfo`](/viewer/python-net/groupdocs.viewer.results/archiveviewinfo/)
