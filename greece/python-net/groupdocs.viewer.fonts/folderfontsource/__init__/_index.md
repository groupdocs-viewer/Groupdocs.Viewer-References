---
title: "Κατασκευαστής __init__"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αρχικοποιεί ένα νέο αντικείμενο FolderFontSource."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Αρχικοποιεί ένα νέο παράδειγμα του [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| folder_path | `str` | Διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType. |
| search_option | `SearchOption` | Καθορίζει αν θα αναζητηθεί μόνο ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υπο‑φάκελοι. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Αν `folder_path` είναι None. |
| `FileNotFoundError` | Αν η διαδρομή που καθορίστηκε στο `folder_path` δεν μπορεί να εντοπιστεί. |

### Παράδειγμα

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Καταχωρίστε τις πηγές γραμματοσειρών για την απόδοση
FontSettings.set_font_sources(src1, src2)

# Μετά την ολοκλήρωση, επαναφέρετε για να αποφύγετε διαρροές πηγών
FontSettings.reset_font_sources()
```

### Δείτε επίσης
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
