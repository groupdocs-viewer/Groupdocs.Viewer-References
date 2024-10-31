---
title: CadViewInfo
second_title: GroupDocs.Viewer for Java API Reference
description: Represents view information for a CAD drawing.
type: docs
weight: 13
url: /java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Represents view information for a CAD drawing.

The CadViewInfo interface defines the contract for retrieving view information specific to a CAD drawing in the GroupDocs.Viewer component. It provides methods to access to CAD drawings layers.

Example usage:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Methods

| Method | Description |
| --- | --- |
| [getLayers()](#getLayers--) | Retrieves the list of layers in the CAD drawing. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Sets the list of layers in the CAD drawing. |
| [getLayouts()](#getLayouts--) | Retrieves the list of layouts contained within the CAD drawing. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Sets the list of layouts contained within the CAD drawing. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Retrieves the list of layers in the CAD drawing.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - the layers in the CAD drawing.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Sets the list of layers in the CAD drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | the layers to set for the CAD drawing. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Retrieves the list of layouts contained within the CAD drawing.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - the layouts in the CAD drawing.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Sets the list of layouts contained within the CAD drawing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | the layouts to set for the CAD drawing. |

