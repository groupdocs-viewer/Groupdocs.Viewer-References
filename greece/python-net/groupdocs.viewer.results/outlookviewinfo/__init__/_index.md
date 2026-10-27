---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του OutlookViewInfo."
type: docs
url: /el/python-net/groupdocs.viewer.results/outlookviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί μια νέα παρουσία του [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-folders}

Αρχικοποιεί μια νέα παρουσία του OutlookViewInfo.

```python
def __init__(self, file_type, pages, folders):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου. |
| pages | `List[Page]` | Η λίστα των σελίδων προς προβολή. |
| folders | `List[str]` | Η λίστα των φακέλων που περιέχονται στο αρχείο δεδομένων Outlook. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εκτοξεύεται όταν το `folders` είναι None. |

### Δείτε επίσης
* class [`OutlookViewInfo`](/viewer/python-net/groupdocs.viewer.results/outlookviewinfo/)
