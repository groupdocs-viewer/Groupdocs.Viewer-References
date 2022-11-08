---
title: Page
second_title: GroupDocs.Viewer for Java API Reference
description: Represents single page that can be viewed.
type: docs
weight: 21
url: /java/com.groupdocs.viewer.results/page/
---```
public interface Page
```

Represents single page that can be viewed. Default implementation is PageImpl
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | The worksheet or page name. |
| [getNumber()](#getNumber--) | The page number. |
| [isVisible()](#isVisible--) | The page visibility indicator. |
| [getWidth()](#getWidth--) | The width of the page in pixels when viewing as JPG or PNG. |
| [getHeight()](#getHeight--) | The height of the page in pixels when viewing as JPG or PNG. |
| [getLines()](#getLines--) | The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction. |
### getName() {#getName--}
```
public abstract String getName()
```


The worksheet or page name.

**Returns:**
java.lang.String
### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


The page number.

**Returns:**
int
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


The page visibility indicator.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


The width of the page in pixels when viewing as JPG or PNG.

**Returns:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


The height of the page in pixels when viewing as JPG or PNG.

**Returns:**
int
### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


The lines contained by the page when viewing as JPG or PNG with enabled Text Extraction.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line>
