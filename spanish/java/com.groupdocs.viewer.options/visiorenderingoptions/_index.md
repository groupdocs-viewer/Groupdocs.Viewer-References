---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Contiene opciones para renderizar documentos Visio."
type: docs
weight: 36
url: /es/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Contiene opciones para renderizar documentos Visio.


La clase VisioRenderingOptions proporciona opciones para procesar y renderizar archivos Visio
en el componente GroupDocs.Viewer. Encapsula configuraciones y parámetros que pueden usarse
para controlar el proceso de renderizado y el formato de salida de documentos Visio.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


Ejemplo de uso:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | Inicializa una nueva instancia de la |
VisioRenderingOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Renderizar solo figuras de Visio, excluyendo el diagrama. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Establece la bandera para renderizar solo figuras de Visio, excluyendo el diagrama. |
|
|  | [getFigureWidth()](#getFigureWidth--) | Obtiene el ancho de la figura. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Establece el ancho de la figura. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Inicializa una nueva instancia de la
VisioRenderingOptions
clase.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Renderizar solo figuras de Visio, excluyendo el diagrama.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Returns:**
boolean -  true  si solo se deben renderizar figuras de Visio,  false  de lo contrario.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Establece la bandera para renderizar solo figuras de Visio, excluyendo el diagrama.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  para renderizar solo figuras de Visio,  false  para incluir el diagrama. |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


Obtiene el ancho de la figura. La altura se calculará automáticamente.


**Returns:**
int - el ancho de la figura.

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


Establece el ancho de la figura. La altura se calculará automáticamente.


***Note:** Default value is 100.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | figureWidth | int | El ancho de la figura. |
|

