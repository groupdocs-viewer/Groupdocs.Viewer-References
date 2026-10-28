---
title: "FontSettings‑klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-teckensnitt."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Tillhandahåller metoder för att arbeta med källor för att söka efter TrueType-teckensnitt.

FontSettings‑typen visar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Återställer typsnittskällor som har ställts in tidigare. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Anger källorna för att söka efter TrueType‑typsnitt vid rendering av dokument. |

### Exempel

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Ställ in typsnittskällor med olika argumentformer (plattas ut internt)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Rensa alla registrerade typsnittskällor
FontSettings.reset_font_sources()
```

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
