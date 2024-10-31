---
title: Page
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a single page that can be viewed.
type: docs
weight: 21
url: /java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

Represents a single page that can be viewed.

The Page interface defines the contract for accessing and manipulating a single page that can be viewed in the GroupDocs.Viewer component. It provides methods to retrieve information such as the page number, size, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Retrieves the name of the worksheet or page. |
| [setName(String name)](#setName-java.lang.String-) | Sets the name of the worksheet or page. |
| [getNumber()](#getNumber--) | Retrieves the page number. |
| [setNumber(int number)](#setNumber-int-) | Sets the page number. |
| [isVisible()](#isVisible--) | Retrieves the page visibility indicator. |
| [setVisible(boolean visible)](#setVisible-boolean-) | Sets the page visibility indicator. |
| [getWidth()](#getWidth--) | Retrieves the width of the page in pixels when viewing as JPG or PNG. |
| [setWidth(int width)](#setWidth-int-) | Sets the width of the page in pixels when viewing as JPG or PNG. |
| [getHeight()](#getHeight--) | Retrieves the height of the page in pixels when viewing as JPG or PNG. |
| [setHeight(int height)](#setHeight-int-) | Sets the height of the page in pixels when viewing as JPG or PNG. |
| [getLines()](#getLines--) | Retrieves the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction. |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | Sets the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction. |
### getName() {#getName--}
```
public abstract String getName()
```


Retrieves the name of the worksheet or page.

**Returns:**
java.lang.String - the name of the worksheet or page.
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


Sets the name of the worksheet or page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | the name to set for the worksheet or page. |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Retrieves the page number.

**Returns:**
int - the page number.
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


Sets the page number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | int | the page number to set. |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Retrieves the page visibility indicator.

**Returns:**
boolean - the page visibility indicator.
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


Sets the page visibility indicator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| visible | boolean | true if the page is visible, false otherwise. |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Retrieves the width of the page in pixels when viewing as JPG or PNG.

**Returns:**
int - the width of the page.
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


Sets the width of the page in pixels when viewing as JPG or PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | int | the width to set for the page. |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Retrieves the height of the page in pixels when viewing as JPG or PNG.

**Returns:**
int - the height of the page.
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


Sets the height of the page in pixels when viewing as JPG or PNG.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | int | the height to set for the page. |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Retrieves the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - the lines contained in the page.
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


Sets the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lines | java.util.List<com.groupdocs.viewer.results.Line> | the list of lines to set for the page. |

