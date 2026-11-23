---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Java API-referentie"
description: "Stelt weergave‑informatie voor een CAD‑tekening voor."
type: docs
weight: 13
url: /nl/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Stelt weergave‑informatie voor een CAD‑tekening voor.


De CadViewInfo‑interface definieert het contract voor het ophalen van weergave‑informatie specifiek voor een CAD‑tekening
in de GroupDocs.Viewer‑component. Het biedt methoden om toegang te krijgen tot CAD‑tekeninglagen.


Voorbeeldgebruik:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getLayers()](#getLayers--) | Haalt de lijst met lagen in de CAD‑tekening op. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Stelt de lijst met lagen in de CAD‑tekening in. |
|
|  | [getLayouts()](#getLayouts--) | Haalt de lijst met lay-outs op die zich in de CAD-tekening bevinden. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Stelt de lijst met lay-outs in die zich in de CAD-tekening bevinden. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Haalt de lijst met lagen in de CAD‑tekening op.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - de lagen in de CAD-tekening.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Stelt de lijst met lagen in de CAD‑tekening in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | de lagen die moeten worden ingesteld voor de CAD-tekening. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Haalt de lijst met lay-outs op die zich in de CAD-tekening bevinden.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - de lay-outs in de CAD-tekening.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Stelt de lijst met lay-outs in die zich in de CAD-tekening bevinden.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | de lay-outs die moeten worden ingesteld voor de CAD-tekening. |
|

