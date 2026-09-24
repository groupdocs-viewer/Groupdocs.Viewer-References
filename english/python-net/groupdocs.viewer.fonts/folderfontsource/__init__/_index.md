---
title: __init__ constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Initializes a new instance of FolderFontSource."
type: docs
url: /python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---


## __init__ {#folder_path-search_option}

Initializes a new instance of [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/).

```python
def __init__(self, folder_path, search_option):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| folder_path | `str` | Path to the folder that contains TrueType fonts. |
| search_option | `SearchOption` | Specifies whether to search the current folder only or the current folder and all sub‑folders. |

| Raises | Description |
| :- | :- |
| `ValueError` | If `folder_path` is None. |
| `FileNotFoundError` | If the path specified in `folder_path` cannot be located. |

### Example

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption, FontSettings

src1 = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
src2 = FolderFontSource("C:/fonts/backup", SearchOption.TOP_FOLDER_ONLY)

# Register the font sources for rendering
FontSettings.set_font_sources(src1, src2)

# When done, reset to avoid leaking sources
FontSettings.reset_font_sources()
```

### See Also
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/)
