---
title: Layout
second_title: GroupDocs.Viewer for Java API Reference
description: Represents layout contained by the CAD drawing.
type: docs
weight: 17
url: /java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Represents layout contained by the CAD drawing. Default implementation is LayoutImpl
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | The name of the layout. |
| [getWidth()](#getWidth--) | The width of the layout. |
| [getHeight()](#getHeight--) | The height of the layout. |
| [equals(Object other)](#equals-java.lang.Object-) | Checks equality |
### getName() {#getName--}
```
public abstract String getName()
```


The name of the layout.

**Returns:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


The width of the layout.

**Returns:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


The height of the layout.

**Returns:**
double
### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Checks equality

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | object to compare |

**Returns:**
boolean - true if equal, otherwise false
