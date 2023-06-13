---
title: Layer
second_title: GroupDocs.Viewer for Java API Reference
description: Represents a layer contained by a CAD drawing.
type: docs
weight: 16
url: /java/com.groupdocs.viewer.results/layer/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Layer extends Serializable
```

Represents a layer contained by a CAD drawing.

The Layer interface defines the contract for accessing and manipulating a layer within a CAD drawing in the GroupDocs.Viewer component. It provides methods to retrieve information such as the layer name, visibility, and other properties.

Example usage:

```

 try (Viewer viewer = new Viewer("document.mpt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List layers = viewInfo.getLayers();
     for (Layer layer : layers) {
         // Use the layer object for further operations
     }
 }
 
```

Note: The default implementation of this interface is LayerImpl.
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Retrieves the name of the layer. |
| [isVisible()](#isVisible--) | Checks the visibility of the layer. |
| [equals(Object other)](#equals-java.lang.Object-) | Checks if this object is equal to the provided object. |
### getName() {#getName--}
```
public abstract String getName()
```


Retrieves the name of the layer.

**Note:** Layer names are case sensitive.

**Returns:**
java.lang.String - the name of the layer.
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


Checks the visibility of the layer.

The CAD drawing layers that are switched off or frozen are invisible. To render layers that are invisible, use the [CadOptions.setLayers(List)](../../com.groupdocs.viewer.options/cadoptions\#setLayers-List-) option.

**Returns:**
boolean -  true  if the layer is visible,  false  otherwise.
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
