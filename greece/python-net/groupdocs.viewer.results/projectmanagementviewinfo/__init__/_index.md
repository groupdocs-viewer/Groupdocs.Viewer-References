---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο του ProjectManagementViewInfo."
type: docs
url: /el/python-net/groupdocs.viewer.results/projectmanagementviewinfo/__init__/
is_root: false
weight: 10
---


## __init__

Δημιουργεί μια νέα παρουσία του [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/).

```python
def __init__(self):
    ...
```

## __init__ {#file_type-pages-start_date-end_date}

Αρχικοποιεί ένα νέο στιγμιότυπο του ProjectManagementViewInfo.

```python
def __init__(self, file_type, pages, start_date, end_date):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου. |
| pages | `List[Page]` | Η λίστα των σελίδων προς προβολή. |
| start_date | `datetime` | Η ημερομηνία και ώρα από την οποία ξεκίνησε το έργο. |
| end_date | `datetime` | Η ημερομηνία και ώρα κατά την οποία το έργο πρέπει να ολοκληρωθεί. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν `pages` είναι None. |

### Δείτε επίσης
* class [`ProjectManagementViewInfo`](/viewer/python-net/groupdocs.viewer.results/projectmanagementviewinfo/)
