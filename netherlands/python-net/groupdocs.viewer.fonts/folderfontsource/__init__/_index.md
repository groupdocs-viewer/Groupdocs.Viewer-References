---
title: "__init__ constructor"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van FolderFontSource."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initialiseert een nieuw exemplaar van [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| folder_path | `str` | Pad naar de map die TrueType‑lettertypen bevat. |
| search_option | `SearchOption` | Specificeert of alleen de huidige map moet worden doorzocht of de huidige map en alle sub‑mappen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Als `folder_path` None is. |
| `FileNotFoundError` | Als het pad opgegeven in `folder_path` niet kan worden gevonden. |

### Voorbeeld

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Registreer de lettertype‑bronnen voor weergave
FontSettings.set_font_sources(src1, src2)

# Na voltooiing, resetten om lekken van bronnen te voorkomen
FontSettings.reset_font_sources()
```

### Zie ook
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
