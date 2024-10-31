---
title: Attachment
second_title: GroupDocs.Viewer for Java API Reference
description: Represents an attachment file contained by an email message archive PDF document or Outlook data file.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.results/attachment/
---```
public interface Attachment
```

Represents an attachment file contained by an email message, archive, PDF document, or Outlook data file.

The Attachment interface defines the contract for accessing and manipulating attachment files in the GroupDocs.Viewer component. It provides methods to retrieve information such as file name, size, and content type of the attachment.

Example usage:

```

 try (Viewer viewer = new Viewer("document.eml")) {
     List attachments = viewer.getAttachments();

     // Use the attachments object for further operations
 }
 
```

***Note:** The default implementation of this interface is AttachmentImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Retrieves the unique identifier of the attachment within the context of a single file that contains this attachment. |
| [setId(String id)](#setId-java.lang.String-) | Sets the unique identifier of the attachment. |
| [getFileName()](#getFileName--) | Retrieves the file name of the attachment. |
| [setFileName(String fileName)](#setFileName-java.lang.String-) | Sets the file name of the attachment. |
| [getFilePath()](#getFilePath--) | Retrieves the relative path of the attachment. |
| [setFilePath(String filePath)](#setFilePath-java.lang.String-) | Sets the relative path of the attachment. |
| [getSize()](#getSize--) | Retrieves the file size of the attachment in bytes. |
| [setSize(long size)](#setSize-long-) | Sets the file size of the attachment in bytes. |
| [getFileType()](#getFileType--) | Retrieves the file type of the attachment. |
| [setFileType(FileType fileType)](#setFileType-com.groupdocs.viewer.FileType-) | Sets the file type of the attachment. |
### getId() {#getId--}
```
public abstract String getId()
```


Retrieves the unique identifier of the attachment within the context of a single file that contains this attachment.

**Returns:**
java.lang.String - the unique identifier of the attachment.
### setId(String id) {#setId-java.lang.String-}
```
public abstract void setId(String id)
```


Sets the unique identifier of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | java.lang.String | the unique identifier to set. |

### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


Retrieves the file name of the attachment.

**Returns:**
java.lang.String - the file name of the attachment.
### setFileName(String fileName) {#setFileName-java.lang.String-}
```
public abstract void setFileName(String fileName)
```


Sets the file name of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | the file name to set. |

### getFilePath() {#getFilePath--}
```
public abstract String getFilePath()
```


Retrieves the relative path of the attachment. The path can be in the format "folder/file.docx" when the file is located within a folder, or it can be the filename when the file is located in the root of an archive, an e-mail message, or a data file.

**Returns:**
java.lang.String - the relative path of the attachment.
### setFilePath(String filePath) {#setFilePath-java.lang.String-}
```
public abstract void setFilePath(String filePath)
```


Sets the relative path of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | the relative path to set. |

### getSize() {#getSize--}
```
public abstract long getSize()
```


Retrieves the file size of the attachment in bytes.

**Returns:**
long - the file size of the attachment.
### setSize(long size) {#setSize-long-}
```
public abstract void setSize(long size)
```


Sets the file size of the attachment in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| size | long | the file size to set. |

### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Retrieves the file type of the attachment.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type of the attachment.
### setFileType(FileType fileType) {#setFileType-com.groupdocs.viewer.FileType-}
```
public abstract void setFileType(FileType fileType)
```


Sets the file type of the attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | the file type to set. |

