---
title: FolderFontSource
second_title: GroupDocs.Viewer for Java API Reference
description: Represents the folder that contains TrueType fonts.
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

Represents the folder that contains TrueType fonts.
## Constructors

| Constructor | Description |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Initializes new instance of [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) class. |
## Methods

| Method | Description |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether two [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are the same. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether two [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are not the same. |
| [getFolderPath()](#getFolderPath--) | Path to the folder that contains TrueType fonts. |
| [getSearchOption()](#getSearchOption--) | Specifies whether to search the current folder, or the current folder and all subfolders. |
| [isRecursive()](#isRecursive--) | Checks if fonts would be searched recursively |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Determines whether the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) is the same as specified [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |
| [equals(Object o)](#equals-java.lang.Object-) | Determines whether the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) is the same as specified object. |
| [hashCode()](#hashCode--) | Returns the hash code for the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Initializes new instance of [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderPath | java.lang.String | Path to the folder that contains TrueType fonts. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Specifies whether to search the current folder, or the current folder and all sub-folders. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Determines whether two [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Left [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Right [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |

**Returns:**
boolean -  true  if both [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are the same; otherwise,  false 
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Determines whether two [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are not the same.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Left [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Right [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |

**Returns:**
boolean - \{@code true if both \{@link FolderFontSource\} objects are not the same; otherwise, \{@code false\}
### getFolderPath() {#getFolderPath--}
```
public final String getFolderPath()
```


Path to the folder that contains TrueType fonts.

**Returns:**
java.lang.String
### getSearchOption() {#getSearchOption--}
```
public final SearchOption getSearchOption()
```


Specifies whether to search the current folder, or the current folder and all subfolders.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - whether to search the current folder, or the current folder and all subfolders.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Checks if fonts would be searched recursively

**Returns:**
boolean - true if recursively, otherwise false
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public final boolean equals(FolderFontSource other)
```


Determines whether the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) is the same as specified [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | The object to compare with the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |

**Returns:**
boolean -  true  if both [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) objects are the same; otherwise,  false 
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Determines whether the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) is the same as specified object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| o | java.lang.Object | The object to compare with the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object. |

**Returns:**
boolean -  true  if  obj  parameter is [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) and is the same as current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object; otherwise,  false 
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code for the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object.

**Returns:**
int - A hash code for the current [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) object.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
