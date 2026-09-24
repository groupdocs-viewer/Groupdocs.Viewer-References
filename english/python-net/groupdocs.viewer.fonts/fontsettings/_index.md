---
title: FontSettings class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Provides methods for working with sources to look for TrueType fonts."
type: docs
url: /python-net/groupdocs.viewer.fonts/fontsettings/
is_root: false
weight: 30
---


## FontSettings class

Provides methods for working with sources to look for TrueType fonts.

The FontSettings type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [reset_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/reset_font_sources/) | Resets font sources that have been set before. |
| [set_font_sources](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/set_font_sources/#font_sources) | Sets the sources to look for TrueType fonts when rendering documents. |

### Example

```python
from groupdocs.viewer.fonts import FontSettings, FolderFontSource, SearchOption

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Set font sources using various argument forms (flattened internally)
FontSettings.set_font_sources(src1, src2)          # varargs
FontSettings.set_font_sources([src1, src2])        # single list
FontSettings.set_font_sources([src1], [src2])      # multiple lists (flattened)
FontSettings.set_font_sources([src1, src2], src2)  # mixed — also flattened

# Clear all registered font sources
FontSettings.reset_font_sources()
```

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
