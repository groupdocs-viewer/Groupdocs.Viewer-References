---
title: FolderFontSource
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a folder that contains TrueType fonts.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Represents a folder that contains TrueType fonts.

The FolderFontSource class is used to specify a folder location that contains TrueType fonts. It allows the GroupDocs.Viewer API to access the fonts stored in the specified folder for document rendering purposes.

Example usage:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initializes a new instance of the  FolderFontSource  class. |
## Methods

| Method | Description |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether two  FolderFontSource  objects are the same. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether two  FolderFontSource  objects are not the same. |
| [getFolderPath()](#getFolderPath--) | Gets the path to the folder that contains TrueType fonts. |
| [getSearchOption()](#getSearchOption--) | Gets the search option that specifies whether to search the current folder, or the current folder and all subfolders. |
| [isRecursive()](#isRecursive--) | Checks if the fonts would be searched recursively. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether the current  FolderFontSource  is the same as the specified  FolderFontSource  object. |
| [equals(Object o)](#equals-java.lang.Object-) | Determines whether the current  FolderFontSource  is the same as the specified object. |
| [hashCode()](#hashCode--) | Returns the hash code for the current  FolderFontSource  object. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initializes a new instance of the  FolderFontSource  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String | Path to the folder that contains TrueType fonts. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Specifies whether to search the current folder, or the current folder and all sub-folders. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Determines whether two  FolderFontSource  objects are the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The left  FolderFontSource  object. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The right  FolderFontSource  object. |

**Returns:**
boolean -  true  if both  FolderFontSource  objects are the same; otherwise,  false .
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Determines whether two  FolderFontSource  objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The left  FolderFontSource  object. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The right  FolderFontSource  object. |

**Returns:**
boolean -  true  if both  FolderFontSource  objects are not the same; otherwise,  false .
### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Gets the path to the folder that contains TrueType fonts.

**Returns:**
java.lang.String - the path to the folder that contains TrueType fonts.
### getSearchOption() {#getSearchOption--}
```
public final SearchOption getSearchOption()
```


Gets the search option that specifies whether to search the current folder, or the current folder and all subfolders.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Checks if the fonts would be searched recursively.

**Returns:**
boolean -  true  if the fonts would be searched recursively,  false  otherwise.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public final boolean equals(FolderFontSource other)
```


Determines whether the current  FolderFontSource  is the same as the specified  FolderFontSource  object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The object to compare with the current  FolderFontSource  object. |

**Returns:**
boolean -  true  if both  FolderFontSource  objects are the same; otherwise,  false 
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Determines whether the current  FolderFontSource  is the same as the specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare with the current  FolderFontSource  object. |

**Returns:**
boolean -  true  if the  obj  parameter is of type  FolderFontSource  and is the same as the current  FolderFontSource  object; otherwise,  false 
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for the current  FolderFontSource  object.

**Returns:**
int - A hash code for the current  FolderFontSource  object.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
