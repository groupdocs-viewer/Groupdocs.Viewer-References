---
title: "Classe FontSettings"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Fournit des méthodes pour travailler avec les sources afin de rechercher les polices TrueType."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Fournit des méthodes pour travailler avec les sources afin de rechercher les polices TrueType.

Le type FontSettings expose les membres suivants :

### Méthodes
| Méthode | Description |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Réinitialise les sources de police qui ont été définies auparavant. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Définit les sources à rechercher pour les polices TrueType lors du rendu des documents. |

### Exemple

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Définir les sources de police en utilisant diverses formes d'arguments (aplatis en interne)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Effacer toutes les sources de police enregistrées
FontSettings.reset_font_sources()
```

### Voir aussi
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
