---
title: TextElement
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a generic text element.
type: docs
weight: 24
url: /java/com.groupdocs.viewer.results/textelement/
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
| [setValue(T value)](#setValue-T-) | Sets the value of the text element. |
| [getX()](#getX--) | Retrieves the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [setX(double x)](#setX-double-) | Sets the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [getY()](#getY--) | Retrieves the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [setY(double y)](#setY-double-) | Sets the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins. |
| [getWidth()](#getWidth--) | Retrieves the width of the rectangle that contains the element (in pixels). |
| [setWidth(double width)](#setWidth-double-) | Sets the width of the rectangle that contains the element (in pixels). |
| [getHeight()](#getHeight--) | Retrieves the height of the rectangle that contains the element (in pixels). |
| [setHeight(double height)](#setHeight-double-) | Sets the height of the rectangle that contains the element (in pixels). |
### getValue() {#getValue--}
```
public abstract T getValue()
```


Retrieves the value of the text element.

**Returns:**
T - the value of the text element.
### setValue(T value) {#setValue-T-}
```
public abstract void setValue(T value)
```


Sets the value of the text element.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The new value to be set for the text element. |

### getX() {#getX--}
```
public abstract double getX()
```


Retrieves the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Returns:**
double - the X coordinate of the starting point.
### setX(double x) {#setX-double-}
```
public abstract void setX(double x)
```


Sets the X coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | The new X coordinate. |

### getY() {#getY--}
```
public abstract double getY()
```


Retrieves the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Returns:**
double - the Y coordinate of the starting point.
### setY(double y) {#setY-double-}
```
public abstract void setY(double y)
```


Sets the Y coordinate of the highest left point on the page layout where the rectangle that contains the element begins.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| y | double | The new Y coordinate. |

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retrieves the width of the rectangle that contains the element (in pixels).

**Returns:**
double - the width of the rectangle.
### setWidth(double width) {#setWidth-double-}
```
public abstract void setWidth(double width)
```


Sets the width of the rectangle that contains the element (in pixels).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | double | The new width. |

### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Retrieves the height of the rectangle that contains the element (in pixels).

**Returns:**
double - the height of the rectangle.
### setHeight(double height) {#setHeight-double-}
```
public abstract void setHeight(double height)
```


Sets the height of the rectangle that contains the element (in pixels).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| height | double | The new height. |

