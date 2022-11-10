---
title: FileInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Contains information about file.
type: docs
weight: 15
url: /java/com.groupdocs.viewer.results/fileinfo/
---```
public interface FileInfo
```

Contains information about file. Default implementation is FileInfoImpl
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | The type of the file. |
| [isEncrypted()](#isEncrypted--) | Indicates that file is encrypted. |
| [setEncrypted(boolean encrypted)](#setEncrypted-boolean-) | Indicates that file is encrypted. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


The type of the file.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Indicates that file is encrypted.

**Returns:**
boolean
### setEncrypted(boolean encrypted) {#setEncrypted-boolean-}
```
public abstract void setEncrypted(boolean encrypted)
```


Indicates that file is encrypted.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encrypted | boolean |  |

