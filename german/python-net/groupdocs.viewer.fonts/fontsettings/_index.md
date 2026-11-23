---
title: "FontSettings Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt Methoden bereit, um mit Quellen nach TrueType-Schriftarten zu suchen."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Stellt Methoden bereit, um mit Quellen nach TrueType-Schriftarten zu suchen.

Der FontSettings-Typ stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Setzt zuvor festgelegte Schriftquellen zurück. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Legt die Quellen fest, in denen nach TrueType-Schriften beim Rendern von Dokumenten gesucht wird. |

### Beispiel

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Setzt Schriftquellen mit verschiedenen Argumentformen (intern abgeflacht)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Alle registrierten Schriftquellen löschen
FontSettings.reset_font_sources()
```

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
