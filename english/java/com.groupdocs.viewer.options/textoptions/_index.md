---
title: TextOptions
second_title: GroupDocs.Viewer for Java API Reference
description: Text files splitting to pages options.
type: docs
weight: 29
url: /java/com.groupdocs.viewer.options/textoptions/
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

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


Gets the maximum number of characters per row on a page.

***Note:** The default value is 85.*

**Returns:**
int - the maximum number of characters per row on a page.
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


Sets the maximum number of characters per row on a page.

***Note:** The default value is 85.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxCharsPerRow | int | The maximum number of characters per row on a page. |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


Gets the maximum number of rows per page.

***Note:** The default value is 55.*

**Returns:**
int - the maximum number of rows.
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


Sets the maximum number of rows per page.

***Note:** The default value is 55.*

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| maxRowsPerPage | int | The maximum number of rows. |

