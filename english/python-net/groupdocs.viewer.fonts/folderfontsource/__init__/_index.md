---
title: FolderFontSource constructor
second_title: GroupDocs.Viewer for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.viewer.fonts/folderfontsource/__init__/
is_root: false
weight: 10
---

## __init__ {#System.String-groupdocs.viewer.fonts.SearchOption}

Initializes new instance of [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource) class.



```python
def __init__(self, folder_path, search_option):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| folder_path | System.String | Path to the folder that contains TrueType fonts. |
| search_option | groupdocs.viewer.fonts.SearchOption | Specifies whether to search the current folder, or the current folder and all sub-folders. |
### Exceptions
| Exception | Description |
| :- | :- |
| ArgumentNullException | Thrown when `folder_path` is null. |
| DirectoryNotFoundException | Thrown when path specified in `folder_path` can't be located. |





### See Also
* module [`groupdocs.viewer.fonts`](../../)
* class [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource)
