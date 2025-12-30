---
title: TextOptions
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Text files splitting to pages options.
type: docs
weight: 32
url: /nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

Text files splitting to pages options.

The TextOptions class provides options for splitting text files into pages in the GroupDocs.Viewer component. It allows you to control how text files are divided into individual pages for rendering and viewing purposes.

Example usage:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [TextOptions()](#TextOptions--) | Initializes a new instance of the  TextOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | Gets the maximum number of characters per row on a page. |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | Sets the maximum number of characters per row on a page. |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | Gets the maximum number of rows per page. |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | Sets the maximum number of rows per page. |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


Initializes a new instance of the  TextOptions  class.

For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Gets the maximum number of characters per row on a page.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - the maximum number of characters per row on a page.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Sets the maximum number of characters per row on a page.

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxCharsPerRow | int | The maximum number of characters per row on a page. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Gets the maximum number of rows per page.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - the maximum number of rows.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Sets the maximum number of rows per page.

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxRowsPerPage | int | The maximum number of rows. |

