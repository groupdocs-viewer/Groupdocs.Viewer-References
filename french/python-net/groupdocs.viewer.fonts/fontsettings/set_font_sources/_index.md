---
title: "méthode set_font_sources"
second_title: "Références API de GroupDocs.Viewer pour Python via .NET"
description: "Définit les sources à rechercher pour les polices TrueType lors du rendu des documents."
type: docs
url: /fr/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Définit les sources à rechercher pour les polices TrueType lors du rendu des documents.

La méthode accepte toute combinaison d'objets [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) individuels, de listes de ceux-ci, ou d'un mélange des deux ; toutes les entrées sont aplaties en une seule liste avant d'être appliquées. Les chemins de chaîne sont transmis tels quels et ne sont pas découpés en caractères.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | Les sources de police. |

| Exceptions | Description |
| :- | :- |
| `ValueError` | Lorsque `font_sources` est None. |

### Exemple

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# liste unique
FontSettings.set_font_sources([src1, src2])
# listes multiples (aplatis)
FontSettings.set_font_sources([src1], [src2])
# mixte — également aplati
FontSettings.set_font_sources([src1, src2], src2)
```

### Voir aussi
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
