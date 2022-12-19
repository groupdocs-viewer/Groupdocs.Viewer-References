---
title: Attachment
second_title: GroupDocs.Viewer for Java API Reference
description: Represents attachment file contained by email message archive PDF document or Outlook data file.
type: docs
weight: 12
url: /java/com.groupdocs.viewer.results/attachment/
---```
public interface Attachment
```

Represents attachment file contained by email message, archive, PDF document or Outlook data file. Default implementation is [Attachment](../../com.groupdocs.viewer.results/attachment)
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Unique identifier of the attachment in context of a single file that contains this attachment. |
| [getFileName()](#getFileName--) | Attachment file name. |
| [getFilePath()](#getFilePath--) | Attachment relative path e.g. "folder/file.docx"" or filename when the file is located in the root of an archive, in e-mail message or data file. |
| [getSize()](#getSize--) | Attachment file size in bytes. |
| [getFileType()](#getFileType--) | Attachment file type. |
### getId() {#getId--}
```
public abstract String getId()
```


Unique identifier of the attachment in context of a single file that contains this attachment.

**Returns:**
java.lang.String
### getFileName() {#getFileName--}
```
public abstract String getFileName()
```


Attachment file name.

**Returns:**
java.lang.String
### getFilePath() {#getFilePath--}
```
public abstract String getFilePath()
```


Attachment relative path e.g. "folder/file.docx"" or filename when the file is located in the root of an archive, in e-mail message or data file.

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public abstract long getSize()
```


Attachment file size in bytes.

**Returns:**
long
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Attachment file type.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype)
