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

***Note:** The  ArchiveOptions  class provides a range of customization options for rendering archive files. You can configure these options based on your specific requirements to achieve the desired output.*
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

By default, GroupDocs.Viewer renders items from all folders contained in the archive. To render items from a specific folder, set this property. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-archive-files/#render-a-specific-folder

**Returns:**
java.lang.String - the folder to be rendered.
### setFolder(String value) {#setFolder-java.lang.String-}
```
public final void setFolder(String value)
```


Sets the folder inside the archive that will be used for rendering.

By default, GroupDocs.Viewer renders items from all folders contained in the archive. To render items from a specific folder, set this property. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#render-a-specific-folder

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The folder to be rendered. |

### getFileName() {#getFileName--}
```
public FileName getFileName()
```


Gets the filename to be displayed in the header.

By default, GroupDocs.Viewer displays the archive file name in the header of each page. To change or hide this name, set this property. For more information and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Returns:**
[FileName](../../com.groupdocs.viewer.options/filename) - the filename to be displayed.
### setFileName(FileName fileName) {#setFileName-com.groupdocs.viewer.options.FileName-}
```
public void setFileName(FileName fileName)
```


Sets the filename to be displayed in the header.

By default, GroupDocs.Viewer displays the archive file name in the header of each page. To change or hide this name, set this property. For more information and code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-archive-files/#specify-the-archive-file-name

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | [FileName](../../com.groupdocs.viewer.options/filename) | The filename to be displayed. |

