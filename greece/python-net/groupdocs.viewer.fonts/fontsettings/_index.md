---
title: "Κλάση FontSettings"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Παρέχει μεθόδους για εργασία με πηγές για την αναζήτηση γραμματοσειρών TrueType."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Παρέχει μεθόδους για εργασία με πηγές για την αναζήτηση γραμματοσειρών TrueType.

Ο τύπος FontSettings εκθέτει τα ακόλουθα μέλη:

### Μέθοδοι
| Μέθοδος | Περιγραφή |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Επαναφέρει τις πηγές γραμματοσειρών που είχαν οριστεί προηγουμένως. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Ορίζει τις πηγές για την αναζήτηση γραμματοσειρών TrueType κατά την απόδοση εγγράφων. |

### Παράδειγμα

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Ορίστε πηγές γραμματοσειρών χρησιμοποιώντας διάφορες μορφές ορισμάτων (εσωτερικά επίπεδοι).
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Καθαρίστε όλες τις καταχωρημένες πηγές γραμματοσειρών
FontSettings.reset_font_sources()
```

### Δείτε επίσης
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
