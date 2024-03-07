---
title: Layout
second_title: GroupDocs.Viewer for Node.js via Java API Reference
description: Represents a layout contained by a CAD drawing.
type: docs
weight: 17
url: /nodejs-java/com.groupdocs.viewer.results/layout/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layout extends Serializable
```

Represents a layout contained by a CAD drawing.

The Layout interface defines the contract for accessing and manipulating a layout within a CAD drawing in the GroupDocs.Viewer component. It provides methods to retrieve information such as the layout name, dimensions, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layouts = viewInfo.getLayouts();
     for (Layout layout : layouts) {
         // Use the layout object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is LayoutImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Retrieves the name of the layout. |
| [getWidth()](#getWidth--) | Retrieves the width of the layout. |
| [getHeight()](#getHeight--) | Retrieves the height of the layout. |
| [equals(Object other)](#equals-java.lang.Object-) | Checks if this object is equal to the provided object. |
### getName() {#getName--}
```
public abstract String getName()
```


Retrieves the name of the layout.

**Returns:**
java.lang.String - the name of the layout.
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Retrieves the width of the layout.

**Returns:**
double - the width of the layout.
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```


Retrieves the height of the layout.

**Returns:**
double - the height of the layout.
### equals(Object other) {#equals-java.lang.Object-}
```
public abstract boolean equals(Object other)
```


Checks if this object is equal to the provided object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | The object to compare. |

**Returns:**
boolean -  true  if the objects are equal,  false  otherwise.
