---
title: set_font_sources method
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Sets the sources to look for TrueType fonts when rendering documents."
type: docs
url: /python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/
is_root: false
weight: 1020
---


## set_font_sources {#font_sources}

Sets the sources to look for TrueType fonts when rendering documents.

The method accepts any combination of individual [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) objects, lists of them, or a mixture of both; all inputs are flattened into a single list before being applied. String paths are passed through as‑is and are not split into characters.

```python
def set_font_sources(cls, font_sources):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| font_sources | `list[IFontSource]` | The font sources. |

| Raises | Description |
| :- | :- |
| `ValueError` | When `font_sources` is None. |

### Example

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# varargs
FontSettings.set_font_sources(src1, src2)
# single list
FontSettings.set_font_sources([src1, src2])
# multiple lists (flattened)
FontSettings.set_font_sources([src1], [src2])
# mixed — also flattened
FontSettings.set_font_sources([src1, src2], src2)
```

### See Also
* class [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/)
