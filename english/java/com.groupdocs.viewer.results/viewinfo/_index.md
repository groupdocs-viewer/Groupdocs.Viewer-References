---
title: ViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for a generic document.
type: docs
weight: 25
url: /java/com.groupdocs.viewer.results/viewinfo/
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
| [getPages()](#getPages--) | Retrieves the list of pages to view. |
### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


Retrieves the type of the file.

**Returns:**
[FileType](../../com.groupdocs.viewer/filetype) - the file type.
### getPages() {#getPages--}
```
public abstract List<Page> getPages()
```


Retrieves the list of pages to view.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Page> - the list of pages.
