---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer für Node.js über Java API-Referenz"
description: "Stellt Ansichtsinformationen für eine CAD‑Zeichnung dar."
type: docs
weight: 13
url: /de/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Stellt Ansichtsinformationen für eine CAD‑Zeichnung dar.

Das CadViewInfo-Interface definiert den Vertrag zum Abrufen von Ansichtsinformationen, die spezifisch für eine CAD-Zeichnung in der GroupDocs.Viewer-Komponente sind. Es stellt Methoden zum Zugriff auf die Ebenen von CAD-Zeichnungen bereit.

Beispielhafte Verwendung:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLayers()](#getLayers--) | Ruft die Liste der Ebenen in der CAD-Zeichnung ab. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Setzt die Liste der Ebenen in der CAD-Zeichnung. |
| [getLayouts()](#getLayouts--) | Ruft die Liste der Layouts ab, die in der CAD-Zeichnung enthalten sind. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Setzt die Liste der Layouts, die in der CAD-Zeichnung enthalten sind. |
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


Setzt die Liste der Ebenen in der CAD-Zeichnung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ebenen | java.util.List<com.groupdocs.viewer.results.Layer> | die Ebenen, die für die CAD-Zeichnung festgelegt werden sollen. |

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


Setzt die Liste der Layouts, die in der CAD-Zeichnung enthalten sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Layouts | java.util.List<com.groupdocs.viewer.results.Layout> | die Layouts, die für die CAD-Zeichnung festgelegt werden sollen. |

