---
title: "Classe FolderFontSource"
second_title: "Riferimenti API di GroupDocs.Viewer per Python via .NET"
description: "Rappresenta la cartella che contiene i font TrueType."
type: docs
url: /it/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Rappresenta la cartella che contiene i font TrueType.

Il tipo FolderFontSource espone i seguenti membri:

### Costruttori
| Costruttore | Descrizione |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Inizializza una nuova istanza di [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Metodi
| Metodo | Descrizione |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Determina se il corrente FolderFontSource è lo stesso dell'oggetto FolderFontSource specificato. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Determina se il corrente FolderFontSource è lo stesso dell'oggetto specificato. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Restituisce il codice hash per l'oggetto [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) corrente. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Restituisce una stringa che rappresenta l'oggetto corrente. |

### Proprietà
| Proprietà | Descrizione |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Il percorso della cartella che contiene i font TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | L'opzione di ricerca che specifica se cercare nella cartella corrente o nella cartella corrente e in tutte le sottocartelle. |

### Esempio

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Crea una fonte di font che ricerca in tutte le sottocartelle.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Vedi anche
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
