---
title: "costruttore __init__"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Inizializza una nuova istanza di FolderFontSource."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Inizializza una nuova istanza di [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| folder_path | `str` | Percorso della cartella che contiene i font TrueType. |
| search_option | `SearchOption` | Specifica se cercare solo nella cartella corrente o nella cartella corrente e in tutte le sottocartelle. |

| Eccezioni | Descrizione |
| :- | :- |
| `ValueError` | Se `folder_path` è None. |
| `FileNotFoundError` | Se il percorso specificato in `folder_path` non può essere trovato. |

### Esempio

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Registra le font sources per il rendering
FontSettings.set_font_sources(src1, src2)

# Al termine, resetta per evitare perdite di font sources
FontSettings.reset_font_sources()
```

### Vedi anche
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
