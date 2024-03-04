---
title: SearchOption
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Specifies whether to search the current folder or the current folder and all subfolders.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.viewer.fonts/searchoption/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum SearchOption extends Enum<SearchOption>
```

Specifies whether to search the current folder, or the current folder and all subfolders.

The SearchOption enum is used to specify the scope of font search operation in the GroupDocs.Viewer API.

Example usage:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```

***Note:** This enum is typically used to specify strategy of searching fonts in provided directory.*
## Fields

| Field | Description |
| --- | --- |
| [TOP_FOLDER_ONLY](#TOP-FOLDER-ONLY) | Includes only the current folder in a search. |
| [ALL_FOLDERS](#ALL-FOLDERS) | Includes the current folder and all the subfolders in a search. |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### TOP_FOLDER_ONLY {#TOP-FOLDER-ONLY}
```
public static final SearchOption TOP_FOLDER_ONLY
```


Includes only the current folder in a search.

### ALL_FOLDERS {#ALL-FOLDERS}
```
public static final SearchOption ALL_FOLDERS
```


Includes the current folder and all the subfolders in a search.

### values() {#values--}
```
public static SearchOption[] values()
```




**Returns:**
com.groupdocs.viewer.fonts.SearchOption[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SearchOption valueOf(String name)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption)
