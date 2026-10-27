---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz von FolderFontSource."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initialisiert eine neue Instanz von [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| folder_path | `str` | Pfad zu dem Ordner, der TrueType‑Schriftarten enthält. |
| search_option | `SearchOption` | Gibt an, ob nur der aktuelle Ordner oder der aktuelle Ordner und alle Unterordner durchsucht werden sollen. |

| Ausnahmen | Beschreibung |
| :- | :- |
| `ValueError` | Falls `folder_path` None ist. |
| `FileNotFoundError` | Falls der in `folder_path` angegebene Pfad nicht gefunden werden kann. |

### Beispiel

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Registrieren Sie die Schriftquellen für die Darstellung
FontSettings.set_font_sources(src1, src2)

# Wenn fertig, zurücksetzen, um das Leaken von Quellen zu vermeiden
FontSettings.reset_font_sources()
```

### Siehe auch
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
