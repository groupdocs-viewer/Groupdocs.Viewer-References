---
title: PathUtils
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: The PathUtils class provides utility methods for working with file paths.
type: docs
weight: 11
url: /nodejs-java/com.groupdocs.viewer.utils/pathutils/
---
**Inheritance:**
java.lang.Object
```
public class PathUtils
```

The PathUtils class provides utility methods for working with file paths.

The PathUtils class contains static methods that allow you to perform various operations on file paths in the GroupDocs.Viewer component.

Example usage:

```

 String combinedPath = PathUtils.combine("part", "of", "path");
 String fileName = PathUtils.getFileName("/path/to/file.txt");
 
```
## Methods

| Method | Description |
| --- | --- |
| [combine(String[] params)](#combine-java.lang.String...-) | Combine paths parts using separator. |
| [getFileName(String path)](#getFileName-java.lang.String-) | Gets file name. |
### combine(String[] params) {#combine-java.lang.String...-}
```
public static String combine(String[] params)
```


Combine paths parts using separator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| params | java.lang.String[] | the paths parts |

**Returns:**
java.lang.String - the result path
### getFileName(String path) {#getFileName-java.lang.String-}
```
public static String getFileName(String path)
```


Gets file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | the path |

**Returns:**
java.lang.String - the file name
