---
title: "μέθοδος set_font_sources"
second_title: "GroupDocs.Viewer για Python μέσω .NET Αναφορές API"
description: "Ορίζει τις πηγές για την αναζήτηση γραμματοσειρών TrueType κατά την απόδοση εγγράφων."
type: docs
url: /el/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Ορίζει τις πηγές για την αναζήτηση γραμματοσειρών TrueType κατά την απόδοση εγγράφων.

Η μέθοδος δέχεται οποιονδήποτε συνδυασμό μεμονωμένων αντικειμένων [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/), λιστών τους ή μίγμα των δύο· όλες οι εισροές ισοπεδώνται σε μία ενιαία λίστα πριν εφαρμοστούν. Οι διαδρομές συμβολοσειρών περνούν όπως είναι και δεν χωρίζονται σε χαρακτήρες.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Οι πηγές γραμματοσειρών. |

| Αναφέρει | Περιγραφή |
| :- | :- |
| `ValueError` | Όταν `font_sources` είναι None. |

### Παράδειγμα

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# μονή λίστα
FontSettings.set_font_sources([src1, src2])
# πολλαπλές λίστες (εξομαλυνμένες)
FontSettings.set_font_sources([src1], [src2])
# μικτό — επίσης εξομαλυνμένο
FontSettings.set_font_sources([src1, src2], src2)
```

### Δείτε επίσης
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
