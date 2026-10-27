---
title: "Classe FontSettings"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Fornisce metodi per lavorare con le sorgenti alla ricerca di font TrueType.

Il tipo FontSettings espone i seguenti membri:

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Reimposta le sorgenti dei caratteri che sono state impostate in precedenza. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Imposta le sorgenti da cui cercare i caratteri TrueType durante il rendering dei documenti. |

### Esempio

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Imposta le sorgenti dei caratteri usando varie forme di argomento (appiattite internamente)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Cancella tutte le sorgenti di caratteri registrate
FontSettings.reset_font_sources()
```

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
