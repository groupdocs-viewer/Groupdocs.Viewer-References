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
| [getNumber()](#getNumber--) | Retrieves the page number. |
| [isVisible()](#isVisible--) | Retrieves the page visibility indicator. |
| [getWidth()](#getWidth--) | Retrieves the width of the page in pixels when viewing as JPG or PNG. |
| [getHeight()](#getHeight--) | Retrieves the height of the page in pixels when viewing as JPG or PNG. |
| [getLines()](#getLines--) | Retrieves the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction. |
### getName() {#getName--}
```
public abstract String getName()
```


Retrieves the name of the worksheet or page.

**Returns:**
java.lang.String - the name of the worksheet or page.
### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


Retrieves the page number.

**Returns:**
int - the page number.
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Retrieves the page visibility indicator.

**Returns:**
boolean - the page visibility indicator.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Retrieves the width of the page in pixels when viewing as JPG or PNG.

**Returns:**
int - the width of the page.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Retrieves the height of the page in pixels when viewing as JPG or PNG.

**Returns:**
int - the height of the page.
### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


Retrieves the lines contained in the page when viewing as JPG or PNG with enabled Text Extraction.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - the lines contained in the page.
