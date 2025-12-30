---
title: ViewInfo
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents view information for a generic document.
type: docs
weight: 25
url: /nodejs-java/com.groupdocs.viewer.results/viewinfo/
---```
public interface ViewInfo
```

Represents view information for a generic document.

The ViewInfo interface defines the contract for accessing and manipulating view information for a generic document in the GroupDocs.Viewer component. It provides methods to retrieve information such as the file type, pages, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.mpp")) {
     final ViewInfo viewInfo = viewer.getViewInfo(ViewInfoOptions.forPngView());
     if (viewInfo instanceof ProjectManagementViewInfo) {
         ProjectManagementViewInfo projectManagementViewInfo = (ProjectManagementViewInfo) viewInfo;
         // Use the projectManagementViewInfo object for further operations
     }
     // ...
 }
 
```

***Note:** The default implementation of this interface is ViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getFileType()](#getFileType--) | Retrieves the type of the file. |
| [setFileType(FileType fileType)](#setFileType-com.groupdocs.viewer.FileType-) | Sets the file type. |
| [getPages()](#getPages--) | Retrieves the list of pages to view. |
| [setPages(List<Page> pages)](#setPages-java.util.List-com.groupdocs.viewer.results.Page--) | Sets the list of pages. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Retrieves the type of the file.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### setFileType(FileType fileType) {#setFileType-com.groupdocs.viewer.FileType-}
```
public abstract void setFileType(FileType fileType)
```


Sets the file type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileType | [FileType](../../com.groupdocs.viewer/filetype) | The file type to set. |

### getPages() {#getPages--}
```
public abstract List<Page> getPages()
```


Retrieves the list of pages to view.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Page> - the list of pages.
### setPages(List<Page> pages) {#setPages-java.util.List-com.groupdocs.viewer.results.Page--}
```
public abstract void setPages(List<Page> pages)
```


Sets the list of pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pages | java.util.List<com.groupdocs.viewer.results.Page> | The list of pages to set. |

