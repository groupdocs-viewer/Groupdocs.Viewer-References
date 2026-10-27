---
title: "VisioRenderingOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Contiene opciones para renderizar documentos Visio."
type: docs
weight: 36
url: /es/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Contiene opciones para renderizar documentos Visio.

La clase VisioRenderingOptions proporciona opciones para procesar y renderizar archivos Visio en el componente GroupDocs.Viewer. Encapsula configuraciones y parámetros que pueden usarse para controlar el proceso de renderizado y el formato de salida de los documentos Visio. Para más detalles, consulte la [documentation][].

Ejemplo de uso:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | Inicializa una nueva instancia de la clase  VisioRenderingOptions . |
## Métodos

| Método | Descripción |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | Renderiza solo figuras Visio, excluyendo el diagrama. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | Establece la bandera para renderizar solo figuras Visio, excluyendo el diagrama. |
| [getFigureWidth()](#getFigureWidth--) | Obtiene el ancho de la figura. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | Establece el ancho de la figura. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


Inicializa una nueva instancia de la clase  VisioRenderingOptions .

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


Renderiza solo figuras Visio, excluyendo el diagrama.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  si solo se deben renderizar figuras de Visio,  false  en caso contrario.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


Establece la bandera para renderizar solo figuras Visio, excluyendo el diagrama.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  para renderizar solo figuras de Visio,  false  para incluir el diagrama. |

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
| figureWidth | int | El ancho de la figura. |

