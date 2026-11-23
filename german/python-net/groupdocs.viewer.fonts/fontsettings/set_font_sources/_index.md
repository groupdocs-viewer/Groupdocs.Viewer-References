---
title: "Methode set_font_sources"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Legt die Quellen fest, in denen nach TrueType-Schriften beim Rendern von Dokumenten gesucht wird."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Legt die Quellen fest, in denen nach TrueType-Schriften beim Rendern von Dokumenten gesucht wird.

Die Methode akzeptiert jede Kombination aus einzelnen [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) Objekten, Listen davon oder einer Mischung aus beidem; alle Eingaben werden zu einer einzelnen Liste zusammengeführt, bevor sie angewendet werden. Zeichenketten‑Pfade werden unverändert weitergegeben und nicht in einzelne Zeichen aufgeteilt.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Die Schriftquellen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Wenn `font_sources` None ist. |

### Beispiel

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Variable Argumente
FontSettings.set_font_sources(src1, src2)
# einzelne Liste
FontSettings.set_font_sources([src1, src2])
# mehrere Listen (abgeflacht)
FontSettings.set_font_sources([src1], [src2])
# gemischt — ebenfalls abgeflacht
FontSettings.set_font_sources([src1, src2], src2)
```

### Siehe auch
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
