---
title: "Κλάση FolderFontSource"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Αναπαριστά το φάκελο που περιέχει γραμματοσειρές TrueType."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Αναπαριστά το φάκελο που περιέχει γραμματοσειρές TrueType.

Ο τύπος FolderFontSource εκθέτει τα ακόλουθα μέλη:

### Κατασκευαστές
| Κατασκευαστής | Περιγραφή |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Αρχικοποιεί ένα νέο παράδειγμα του [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο FolderFontSource. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Καθορίζει εάν το τρέχον FolderFontSource είναι το ίδιο με το καθορισμένο αντικείμενο. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Επιστρέφει τον κωδικό κατακερματισμού για το τρέχον αντικείμενο [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Επιστρέφει μια συμβολοσειρά που αντιπροσωπεύει το τρέχον αντικείμενο. |

### Ιδιότητες
| Ιδιότητα | Περιγραφή |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Η διαδρομή προς το φάκελο που περιέχει γραμματοσειρές TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Η επιλογή αναζήτησης που καθορίζει εάν θα αναζητηθεί ο τρέχων φάκελος ή ο τρέχων φάκελος και όλοι οι υποφάκελοι. |

### Παράδειγμα

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Δημιουργήστε μια πηγή γραμματοσειρών που αναζητά όλους τους υποφακέλους.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
