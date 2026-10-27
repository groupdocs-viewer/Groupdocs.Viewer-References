---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο στιγμιότυπο του CadViewInfo."
type: docs
url: /el/python-net/groupdocs.viewer.results/cadviewinfo/__init__/
is_root: false
weight: 10
---


## __init__ {#file_type-pages-layers-layouts}

Αρχικοποιεί ένα νέο στιγμιότυπο του CadViewInfo.

```python
def __init__(self, file_type, pages, layers, layouts):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_type | `FileType` | Ο τύπος του αρχείου. |
| pages | `List[Page]` | Η λίστα των σελίδων προς προβολή. |
| layers | `List[Layer]` | Η λίστα των στρώσεων που περιέχονται στο σχέδιο CAD. |
| layouts | `List[Layout]` | Η λίστα των στρώσεων που περιέχονται στο σχέδιο CAD. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Εγείρεται όταν το `layouts` είναι None. |

### Δείτε επίσης
* class [`CadViewInfo`](/viewer/python-net/groupdocs.viewer.results/cadviewinfo/)
