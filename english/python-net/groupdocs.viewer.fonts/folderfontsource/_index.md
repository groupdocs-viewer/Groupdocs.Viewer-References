---
title: FolderFontSource class
second_title: GroupDocs.Viewer for Python via .NET API References
description: "Represents the folder that contains TrueType fonts."
type: docs
url: /python-net/groupdocs.viewer.fonts/folderfontsource/
is_root: false
weight: 10
---


## FolderFontSource class

Represents the folder that contains TrueType fonts.

The FolderFontSource type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/__init__/#folder_path-search_option) | Initializes a new instance of [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/). |

### Methods
| Method | Description |
| :- | :- |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#other) | Determines whether the current FolderFontSource is the same as the specified FolderFontSource object. |
| [equals](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals/#obj) | Determines whether the current FolderFontSource is the same as the specified object. |
| [equals_folder_font_source](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_folder_font_source/) |  |
| [equals_object](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/equals_object/) |  |
| [get_hash_code](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/get_hash_code/) | Returns the hash code for the current [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) object. |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/to_string/) | Returns a string that represents the current object. |

### Properties
| Property | Description |
| :- | :- |
| [folder_path](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/folder_path/) | The path to the folder that contains TrueType fonts. |
| [search_option](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/search_option/) | The search option specifying whether to search the current folder, or the current folder and all subfolders. |

### Example

```python
from groupdocs.viewer.fonts import FolderFontSource, SearchOption

# Create a font source that searches all subfolders.
src = FolderFontSource("C:/fonts/primary", SearchOption.ALL_FOLDERS)
```

### See Also
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
