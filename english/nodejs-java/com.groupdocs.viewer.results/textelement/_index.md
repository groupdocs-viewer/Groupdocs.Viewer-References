---
title: TextElement
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents a generic text element.
type: docs
weight: 24
url: /nodejs-java/com.groupdocs.viewer.results/textelement/
---```
public interface TextElement<T>
```

Represents a generic text element.

The TextElement interface defines the contract for a generic text element in the GroupDocs.Viewer component. It represents a text element with a specific type and provides methods to access and manipulate the text content.

***Note:** The default implementation of this interface is TextElementImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | Retrieves the value of the text element. |
| [getX()](#getX--) | Retrieves the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [getY()](#getY--) | Retrieves the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [getWidth()](#getWidth--) | Retrieves the width of the rectangle that contains the element (in pixels). |
| [getHeight()](#getHeight--) | Retrieves the height of the rectangle that contains the element (in pixels). |
### getValue() {#getValue--}
```
public abstract T getValue()
```


Retrieves the value of the text element.

**Returns:**
T - the value of the text element.
### getX() {#getX--}
```
public abstract double getX()
```


Retrieves the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Returns:**
double - the X coordinate of the starting point.
### getY() {#getY--}
```
public abstract double getY()
```


Retrieves the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Returns:**
double - the Y coordinate of the starting point.
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retrieves the width of the rectangle that contains the element (in pixels).

**Returns:**
double - the width of the rectangle.
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Retrieves the height of the rectangle that contains the element (in pixels).

**Returns:**
double - the height of the rectangle.
