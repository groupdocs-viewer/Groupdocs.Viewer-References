---
title: TextElement
second_title: GroupDocs.Viewer for Java API Reference
description: Represents generic text element.
type: docs
weight: 24
url: /java/com.groupdocs.viewer.results/textelement/
---```
public interface TextElement<T>
```

Represents generic text element.

Default implementation is TextElementImpl
## Methods

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | The element value. |
| [getX()](#getX--) | The X coordinate of the highest left point on the page layout where the rectangle that contains element begins. |
| [getY()](#getY--) | The Y coordinate of the highest left point on the page layout where the rectangle that contains element begins. |
| [getWidth()](#getWidth--) | The width of the rectangle which contains the element (in pixels). |
| [getHeight()](#getHeight--) | The height of the rectangle which contains the element (in pixels). |
### getValue() {#getValue--}
```
public abstract T getValue()
```


The element value.

**Returns:**
T
### getX() {#getX--}
```
public abstract double getX()
```


The X coordinate of the highest left point on the page layout where the rectangle that contains element begins.

**Returns:**
double
### getY() {#getY--}
```
public abstract double getY()
```


The Y coordinate of the highest left point on the page layout where the rectangle that contains element begins.

**Returns:**
double
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


The width of the rectangle which contains the element (in pixels).

**Returns:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


The height of the rectangle which contains the element (in pixels).

**Returns:**
double
