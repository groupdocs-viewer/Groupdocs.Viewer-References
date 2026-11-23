---
title: "Classe FolderFontSource"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Représente le dossier contenant les polices TrueType."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Représente le dossier contenant les polices TrueType.

Le type FolderFontSource expose les membres suivants :

### Constructeurs
| Constructeur | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Initialise une nouvelle instance de [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Méthodes
| Méthode | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Détermine si le FolderFontSource actuel est identique à l'objet FolderFontSource spécifié. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Détermine si le FolderFontSource actuel est identique à l'objet spécifié. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Renvoie le code de hachage de l'objet [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) actuel. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Renvoie une chaîne qui représente l'objet actuel. |

### Propriétés
| Propriété | Description |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | Le chemin vers le dossier contenant les polices TrueType. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | L'option de recherche spécifiant s'il faut rechercher dans le dossier actuel, ou dans le dossier actuel et tous ses sous‑dossiers. |

### Exemple

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Crée une source de police qui recherche dans tous les sous‑dossiers.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
