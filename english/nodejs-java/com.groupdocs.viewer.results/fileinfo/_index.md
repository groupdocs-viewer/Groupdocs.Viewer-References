---
title: FileInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Contains information about a file.
type: docs
weight: 15
url: /nodejs-java/com.groupdocs.viewer.results/fileinfo/
---```
public interface FileInfo
```

Contains information about a file.

The FileInfo interface defines the contract for accessing and retrieving information about a file in the GroupDocs.Viewer component. It provides methods to retrieve details such as the file type, encryption and so on.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pdf")) {
     FileInfo fileInfo = viewer.getFileInfo();

     // Use the fileInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is FileInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Retrieves the type of the file. |
| [isEncrypted()](#isEncrypted--) | Checks if the file is encrypted. |
| [setEncrypted(boolean encrypted)](#setEncrypted-boolean-) | Sets the encryption status of the file. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Retrieves the type of the file.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Checks if the file is encrypted.

**Returns:**
boolean -  true  if the file is encrypted,  false  otherwise.
### setEncrypted(boolean encrypted) {#setEncrypted-boolean-}
```
public abstract void setEncrypted(boolean encrypted)
```


Sets the encryption status of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encrypted | boolean |  true  to indicate that the file is encrypted,  false  otherwise. |

