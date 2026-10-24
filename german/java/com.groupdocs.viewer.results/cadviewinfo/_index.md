---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer für Java API-Referenz"
description: "Stellt Ansichtsinformationen für eine CAD‑Zeichnung dar."
type: docs
weight: 13
url: /de/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für eine CAD‑Zeichnung dar.


Das CadViewInfo-Interface definiert den Vertrag für das Abrufen von Ansichtsinformationen, die spezifisch für eine CAD-Zeichnung sind
in der GroupDocs.Viewer-Komponente. Es bietet Methoden zum Zugriff auf CAD-Zeichnungsebenen.


Beispielverwendung:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLayers()](#getLayers--) | Ruft die Liste der Ebenen in der CAD-Zeichnung ab. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Legt die Liste der Ebenen in der CAD-Zeichnung fest. |
|
|  | [getLayouts()](#getLayouts--) | Ruft die Liste der Layouts ab, die in der CAD-Zeichnung enthalten sind. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Legt die Liste der Layouts fest, die in der CAD-Zeichnung enthalten sind. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Ruft die Liste der Ebenen in der CAD-Zeichnung ab.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - die Ebenen in der CAD-Zeichnung.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Legt die Liste der Ebenen in der CAD-Zeichnung fest.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | die Ebenen, die für die CAD-Zeichnung festgelegt werden sollen. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Ruft die Liste der Layouts ab, die in der CAD-Zeichnung enthalten sind.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - die Layouts in der CAD-Zeichnung.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Legt die Liste der Layouts fest, die in der CAD-Zeichnung enthalten sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | die Layouts, die für die CAD-Zeichnung festgelegt werden sollen. |
|

