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

The  ArchiveOptions  class represents a set of options that can be used to configure the rendering of archive files in the viewer module. It allows you to customize various aspects of the rendering process, such as the count of items on each page and so on.

Example usage:

```

 // Create an instance of ArchiveOptions
 ArchiveOptions options = new ArchiveOptions();

 // Set the count of items to be shown on each page
 options.setItemsPerPage(16);

 // Create a Viewer instance with the specified options
 try (final Viewer viewer = new Viewer(documentPath, options)) {
     // Use the viewer object for document rendering
 }
 
```

Note: The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.
## Constructors

| Constructor | Description |
| --- | --- |
| [ArchiveOptions()](#ArchiveOptions--) | Creates a new instance of the ArchiveOptions class with default settings. |
## Methods

| Method | Description |
| --- | --- |
| [getFolder()](#getFolder--) | Gets the folder inside the archive that will be used for rendering. |
| [setFolder(String value)](#setFolder-java.lang.String-) | Sets the folder inside the archive that will be used for rendering. |
| [getFileName()](#getFileName--) | Gets the filename to be displayed in the header. |
| [setFileName(FileName fileName)](#setFileName-com.groupdocs.viewer.options.FileName-) | Sets the filename to be displayed in the header. |
| [getItemsPerPage()](#getItemsPerPage--) | Gets the number of records per page for rendering to HTML. |
| [setItemsPerPage(int itemsPerPage)](#setItemsPerPage-int-) | Sets the number of records per page for rendering to HTML. |
### ArchiveOptions() {#ArchiveOptions--}
```
public ArchiveOptions()
```


Creates a new instance of the ArchiveOptions class with default settings.

### getFolder() {#getFolder--}
```
public final String getFolder()
```


Gets the folder inside the archive that will be used for rendering.

**Returns:**
java.lang.String - the folder to be rendered.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Sets the folder inside the archive that will be used for rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The folder to be rendered. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Gets the filename to be displayed in the header. By default, the name of the source file is displayed.

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Sets the filename to be displayed in the header. By default, the name of the source file is displayed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | The filename to be displayed. |

### getItemsPerPage() {#getItemsPerPage--}
```
public int getItemsPerPage()
```


Gets the number of records per page for rendering to HTML.

**Returns:**
int - the number of records per page.
### setItemsPerPage(int itemsPerPage) {#setItemsPerPage-int-}
```
public void setItemsPerPage(int itemsPerPage)
```


Sets the number of records per page for rendering to HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | int | The number of records per page. |

