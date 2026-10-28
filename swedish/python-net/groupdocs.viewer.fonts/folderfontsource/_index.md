---
title: "FolderFontSource-klass"
second_title: "GroupDocs.Viewer för Python via .NET API-referenser"
description: "Representerar mappen som innehåller TrueType-teckensnitt."
type: docs
url: /sv/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Representerar mappen som innehåller TrueType-teckensnitt.

FolderFontSource-typen visar följande medlemmar:

### Konstruktorer
| Konstruktor | Beskrivning |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Initierar en ny instans av [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Bestämmer om den aktuella FolderFontSource är densamma som det angivna FolderFontSource-objektet. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Bestämmer om den aktuella FolderFontSource är densamma som det angivna objektet. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Returnerar hashkoden för den aktuella [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) objektet. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Returnerar en sträng som representerar det aktuella objektet. |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Sökvägen till mappen som innehåller TrueType-teckensnitt. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | Sökalternativet som anger om den aktuella mappen ska sökas, eller den aktuella mappen och alla undermappar. |

### Exempel

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Skapa en teckensnittskälla som söker i alla undermappar.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Se även
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
