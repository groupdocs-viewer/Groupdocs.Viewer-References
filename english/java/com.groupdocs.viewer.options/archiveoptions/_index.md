---
title: ArchiveOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Provides options for rendering archive files.
type: docs
weight: 10
url: /java/com.groupdocs.viewer.options/archiveoptions/
---
**Inheritance:**
java.lang.Object
```
public class ArchiveOptions
```

Provides options for rendering archive files.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | The folder inside the archive to be rendered. |
| [setFolder(String value)](#setFolder-java.lang.String-) | The folder inside the archive to be rendered. |
| [getFileName()](#getFileName--) | The filename to display in the header. |
| [setFileName(FileName mFileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | The filename to display in the header. |
| [getItemsPerPage()](#getItemsPerPage--) | Number of records per page (for rendering to HTML only) |
| [setItemsPerPage(int itemsPerPage)](#setItemsPerPage-int-) | Number of records per page (for rendering to HTML only) |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


### getFolder() {#getFolder--}
```
public final String getFolder()
```


The folder inside the archive to be rendered.

**Returns:**
java.lang.String
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


The folder inside the archive to be rendered.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


The filename to display in the header. By default the name of the source file is displayed.

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - The filename
### setFileName(FileName mFileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName mFileName)
```


The filename to display in the header. By default the name of the source file is displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mFileName | [FileName](../../com.groupdocs.viewer.options/filename) | The filename |

### getItemsPerPage() {#getItemsPerPage--}
```
public int getItemsPerPage()
```


Number of records per page (for rendering to HTML only)

**Returns:**
int
### setItemsPerPage(int itemsPerPage) {#setItemsPerPage-int-}
```
public void setItemsPerPage(int itemsPerPage)
```


Number of records per page (for rendering to HTML only)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int |  |

