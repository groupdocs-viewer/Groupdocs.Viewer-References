---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Initialise une nouvelle instance de FolderFontSource."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initialise une nouvelle instance de [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| folder_path | `str` | Chemin du dossier contenant les polices TrueType. |
| search_option | `SearchOption` | Spécifie s'il faut rechercher uniquement le dossier actuel ou le dossier actuel et tous les sous‑dossiers. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Si `folder_path` est None. |
| `FileNotFoundError` | Si le chemin spécifié dans `folder_path` ne peut pas être trouvé. |

### Exemple

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Enregistrez les sources de polices pour le rendu
FontSettings.set_font_sources(src1, src2)

# Une fois terminé, réinitialisez pour éviter les fuites de sources
FontSettings.reset_font_sources()
```

### Voir aussi
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
