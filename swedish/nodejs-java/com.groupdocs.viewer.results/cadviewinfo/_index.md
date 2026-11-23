---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer för Node.js via Java API-referens"
description: "Representerar vyinformation för en CAD-ritning."
type: docs
weight: 13
url: /sv/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Representerar vyinformation för en CAD-ritning.

CadViewInfo-gränssnittet definierar kontraktet för att hämta vyinformation som är specifik för en CAD-ritning i GroupDocs.Viewer-komponenten. Det tillhandahåller metoder för att komma åt CAD-ritningens lager.

Exempel på användning:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLayers()](#getLayers--) | Hämtar listan över lager i CAD-ritningen. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Ställer in listan över lager i CAD-ritningen. |
| [getLayouts()](#getLayouts--) | Hämtar listan över layouter som finns i CAD-ritningen. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Ställer in listan över layouter som finns i CAD-ritningen. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Hämtar listan över lager i CAD-ritningen.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - lagren i CAD-ritningen.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Ställer in listan över lager i CAD-ritningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layers | java.util.List<com.groupdocs.viewer.results.Layer> | lagren som ska ställas in för CAD-ritningen. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Hämtar listan över layouter som finns i CAD-ritningen.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - layouterna i CAD-ritningen.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Ställer in listan över layouter som finns i CAD-ritningen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layouts | java.util.List<com.groupdocs.viewer.results.Layout> | layouterna som ska ställas in för CAD-ritningen. |

