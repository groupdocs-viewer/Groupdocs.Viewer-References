---
title: "CadViewInfo"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Representa información de vista para un dibujo CAD."
type: docs
weight: 13
url: /es/java/com.groupdocs.viewer.results/cadviewinfo/
---
**All Implemented Interfaces:**
[com.groupdocs.viewer.results.ViewInfo](../../com.groupdocs.viewer.results/viewinfo)
```
public interface CadViewInfo extends ViewInfo
```

Representa información de vista para un dibujo CAD.


La interfaz CadViewInfo define el contrato para recuperar información de vista específica de un dibujo CAD
en el componente GroupDocs.Viewer. Proporciona métodos para acceder a las capas de los dibujos CAD.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("document.plt")) {
     CadViewInfo viewInfo = (CadViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());

     // Use the viewInfo object for further operations
 }
 
````


***Note:** The default implementation of this interface is CadViewInfoImpl.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getLayers()](#getLayers--) | Recupera la lista de capas en el dibujo CAD. |
|
|  | [setLayers(List<Layer> layers)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | Establece la lista de capas en el dibujo CAD. |
|
|  | [getLayouts()](#getLayouts--) | Recupera la lista de diseños contenidos en el dibujo CAD. |
|
|  | [setLayouts(List<Layout> layouts)](#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--) | Establece la lista de diseños contenidos en el dibujo CAD. |
|
### getLayers() {#getLayers--}
```
public abstract List<Layer> getLayers()
```


Recupera la lista de capas en el dibujo CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - las capas en el dibujo CAD.

### setLayers(List<Layer> layers) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public abstract void setLayers(List<Layer> layers)
```


Establece la lista de capas en el dibujo CAD.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | layers | java.util.List<com.groupdocs.viewer.results.Layer> | las capas a establecer para el dibujo CAD. |
|

### getLayouts() {#getLayouts--}
```
public abstract List<Layout> getLayouts()
```


Recupera la lista de diseños contenidos en el dibujo CAD.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layout> - los diseños en el dibujo CAD.

### setLayouts(List<Layout> layouts) {#setLayouts-java.util.List-com.groupdocs.viewer.results.Layout--}
```
public abstract void setLayouts(List<Layout> layouts)
```


Establece la lista de diseños contenidos en el dibujo CAD.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | layouts | java.util.List<com.groupdocs.viewer.results.Layout> | los diseños a establecer para el dibujo CAD. |
|

