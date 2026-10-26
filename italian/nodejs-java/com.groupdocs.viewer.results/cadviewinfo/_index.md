---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer per Node.js via Java Riferimento API"
description: "Rappresenta le informazioni di visualizzazione per un disegno CAD."
type: docs
weight: 13
url: /it/nodejs-java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Rappresenta le informazioni di visualizzazione per un disegno CAD.

L'interfaccia CadViewInfo definisce il contratto per il recupero delle informazioni di visualizzazione specifiche di un disegno CAD nel componente GroupDocs.Viewer. Fornisce metodi per accedere ai layer dei disegni CAD.

Esempio di utilizzo:

```

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
```

***Note:** The default implementation of this interface is CadViewInfoImpl.*
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLayers()](#getLayers--) | Recupera l'elenco dei layer nel disegno CAD. |
| [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Imposta l'elenco dei layer nel disegno CAD. |
| [getLayouts()](#getLayouts--) | Recupera l'elenco dei layout contenuti nel disegno CAD. |
| [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Imposta l'elenco dei layout contenuti nel disegno CAD. |
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Recupera l'elenco dei layer nel disegno CAD.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - i layer nel disegno CAD.
### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Imposta l'elenco dei layer nel disegno CAD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| livelli | java.util.List<com.groupdocs.viewer.results.Layer> | i layer da impostare per il disegno CAD. |

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Recupera l'elenco dei layout contenuti nel disegno CAD.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - i layout nel disegno CAD.
### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Imposta l'elenco dei layout contenuti nel disegno CAD.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layout | java.util.List<com.groupdocs.viewer.results.Layout> | i layout da impostare per il disegno CAD. |

