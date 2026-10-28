---
title: "set_font_sources-metod"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Anger källorna för att söka efter TrueType‑typsnitt vid rendering av dokument."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Anger källorna för att söka efter TrueType‑typsnitt vid rendering av dokument.

Metoden accepterar vilken kombination som helst av enskilda [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/)-objekt, listor av dem eller en blandning av båda; alla indata plattas ut till en enda lista innan de tillämpas. Strängvägar skickas igenom oförändrade och delas inte upp i tecken.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Teckensnittskällorna. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | När `font_sources` är None. |

### Exempel

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# enkel lista
FontSettings.set_font_sources([src1, src2])
# flera listor (plattade)
FontSettings.set_font_sources([src1], [src2])
# blandad — också plattad
FontSettings.set_font_sources([src1, src2], src2)
```

### Se även
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
