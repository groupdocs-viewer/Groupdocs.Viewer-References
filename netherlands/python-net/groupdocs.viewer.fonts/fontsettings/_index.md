---
title: "FontSettings‑klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Biedt methoden voor het werken met bronnen om naar TrueType-lettertypen te zoeken."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Biedt methoden voor het werken met bronnen om naar TrueType-lettertypen te zoeken.

Het FontSettings‑type exposeert de volgende leden:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Reset de lettertype‑bronnen die eerder zijn ingesteld. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Stelt de bronnen in om TrueType‑lettertypen te zoeken bij het renderen van documenten. |

### Voorbeeld

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Stel lettertype‑bronnen in met verschillende argumentvormen (intern afgevlakt)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Wis alle geregistreerde lettertype‑bronnen
FontSettings.reset_font_sources()
```

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
