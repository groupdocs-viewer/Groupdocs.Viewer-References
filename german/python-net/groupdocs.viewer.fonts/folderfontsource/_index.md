---
title: "FolderFontSource Klasse"
second_title: "GroupDocs.Viewer für Python über .NET API-Referenzen"
description: "Stellt den Ordner dar, der TrueType-Schriftarten enthält."
type: docs
url: /de/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Stellt den Ordner dar, der TrueType-Schriftarten enthält.

Der Typ FolderFontSource stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Initialisiert eine neue Instanz von [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Bestimmt, ob die aktuelle FolderFontSource dieselbe ist wie das angegebene FolderFontSource-Objekt. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Bestimmt, ob die aktuelle FolderFontSource dieselbe ist wie das angegebene Objekt. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Gibt den Hashcode für das aktuelle [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) Objekt zurück. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Gibt einen String zurück, der das aktuelle Objekt repräsentiert. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Der Pfad zu dem Ordner, der TrueType-Schriftarten enthält. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Die Suchoption, die angibt, ob nur der aktuelle Ordner oder der aktuelle Ordner und alle Unterordner durchsucht werden sollen. |

### Beispiel

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Erstellt eine Schriftquelle, die alle Unterordner durchsucht.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Siehe auch
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
