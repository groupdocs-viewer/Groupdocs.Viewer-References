---
title: "__init__‑konstruktor"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Initierar en ny instans av FolderFontSource."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initierar en ny instans av [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| folder_path | `str` | Sökväg till mappen som innehåller TrueType-teckensnitt. |
| search_option | `SearchOption` | Anger om endast den aktuella mappen ska sökas eller den aktuella mappen och alla undermappar. |

| Uppstår | Beskrivning |
| :- | :- |
| `ValueError` | Om `folder_path` är None. |
| `FileNotFoundError` | Om sökvägen som angavs i `folder_path` inte kan hittas. |

### Exempel

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Registrera teckensnittskällorna för rendering
FontSettings.set_font_sources(src1, src2)

# När du är klar, återställ för att undvika läckage av källor
FontSettings.reset_font_sources()
```

### Se även
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
