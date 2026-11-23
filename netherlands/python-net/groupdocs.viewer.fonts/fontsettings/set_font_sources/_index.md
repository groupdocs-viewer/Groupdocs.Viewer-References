---
title: "set_font_sources methode"
second_title: "GroupDocs.Viewer voor Python via .NET API-referenties"
description: "Stelt de bronnen in om TrueType‑lettertypen te zoeken bij het renderen van documenten."
type: docs
url: /nl/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Stelt de bronnen in om TrueType‑lettertypen te zoeken bij het renderen van documenten.

De methode accepteert elke combinatie van individuele [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) objecten, lijsten daarvan, of een mengsel van beide; alle invoer wordt samengevoegd tot één lijst voordat deze wordt toegepast. String‑paden worden onveranderd doorgegeven en niet opgesplitst in tekens.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | De lettertype‑bronnen. |

| Gooit | Beschrijving |
| :- | :- |
| `ValueError` | Wanneer `font_sources` None is. |

### Voorbeeld

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# enkele lijst
FontSettings.set_font_sources([src1, src2])
# meerdere lijsten (geplat)
FontSettings.set_font_sources([src1], [src2])
# gemengd — ook geplat
FontSettings.set_font_sources([src1, src2], src2)
```

### Zie ook
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
