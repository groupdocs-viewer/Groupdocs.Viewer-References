---
title: FileName
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents the name of a file in an archive.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.viewer.options/filename/
---
**Inheritance:**
java.lang.Object
```
public class FileName
```

Represents the name of a file in an archive.

The FileName class encapsulates the name of a file without any path or directory information. It provides methods to manipulate and retrieve information about the file name.

Example usage:

```

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.getArchiveOptions().setFileName(new FileName("my-file-name"));

 final LoadOptions loadOptions = new LoadOptions(FileType.ZIP);
 try (final Viewer viewer = new Viewer(documentPath, loadOptions)) {
     viewer.view(options);
     // Use the viewer object for archive document rendering
 }
 
```

***Note:** The FileName class is used to work with file names and does not handle file operations or manipulation.*
## Constructors

| Constructor | Description |
| --- | --- |
| [FileName(String fileName)](#FileName-java.lang.String-) | Initializes a new instance of the  FileName  class. |
## Fields

| Field | Description |
| --- | --- |
| [EMPTY](#EMPTY) | Represents an empty filename. |
| [SOURCE](#SOURCE) | Represents the name of the source file. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) |  |
| [toString()](#toString--) | Returns a string representation of the current object. |
### FileName(String fileName) {#FileName-java.lang.String-}
```
public FileName(String fileName)
```


Initializes a new instance of the  FileName  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The name of the file. |

### EMPTY {#EMPTY}
```
public static final FileName EMPTY
```


Represents an empty filename.

### SOURCE {#SOURCE}
```
public static final FileName SOURCE
```


Represents the name of the source file.

### getText() {#getText--}
```
public String getText()
```




**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of the current object.

**Returns:**
java.lang.String - a string representation of the current object.
