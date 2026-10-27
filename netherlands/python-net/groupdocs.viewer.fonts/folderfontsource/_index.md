---
title: "FolderFontSource klasse"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt de map voor die TrueType-lettertypen bevat."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Stelt de map voor die TrueType-lettertypen bevat.

Het type FolderFontSource exposeert de volgende leden:

### Constructors
| Constructor | Beschrijving |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Initialiseert een nieuw exemplaar van [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Bepaalt of de huidige FolderFontSource hetzelfde is als het opgegeven FolderFontSource-object. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Bepaalt of de huidige FolderFontSource hetzelfde is als het opgegeven object. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Retourneert de hashcode voor het huidige [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) object. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Retourneert een string die het huidige object vertegenwoordigt. |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Het pad naar de map die TrueType-lettertypen bevat. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | De zoekoptie die aangeeft of er gezocht moet worden in de huidige map, of in de huidige map en alle submappen. |

### Voorbeeld

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Maak een lettertypebron die alle submappen doorzoekt.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Zie ook
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
