---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί μια νέα παρουσία του LotusNotesViewInfo."
type: docs
url: /el/python-net/groupdocs.viewer.results/lotusnotesviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Αρχικοποιεί ένα νέο στιγμιότυπο του [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-notes_count}

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/).

```python
def __init__(self, file_type, pages, notes_count):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου. |
| pages | `List[Page]` | Η λίστα των σελίδων προς προβολή. |
| notes_count | `int` | Ο αριθμός σημειώσεων που περιέχεται στο αρχείο αποθήκευσης βάσης δεδομένων Lotus. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `notes_count` είναι None. |

### Δείτε επίσης
* class [`LotusNotesViewInfo`](/viewer/python-net/groupdocs.viewer.results/lotusnotesviewinfo/)
