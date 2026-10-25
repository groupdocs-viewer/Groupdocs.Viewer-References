---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos en formato PNG."
type: docs
weight: 25
url: /es/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

Proporciona opciones para renderizar documentos en formato PNG.


La clase PngViewOptions encapsula configuraciones y parámetros adicionales que pueden usarse
para controlar la renderización de documentos en formato PNG en el componente GroupDocs.Viewer.


Ejemplo de uso:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
Para obtener más detalles, consulte esta [página](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) y sus subpáginas.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inicializa una nueva instancia de la |
PngViewOptions
clase.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inicializa una nueva instancia de la |
PngViewOptions
clase.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inicializa una nueva instancia de la |
PngViewOptions
clase.
|
|  | [PngViewOptions()](#PngViewOptions--) | Inicializa una nueva instancia de |
PngViewOptions
clase.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | Inicializa una nueva instancia de la |
PngViewOptions
clase.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | Inicializa una nueva instancia de la |
PngViewOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Devuelve el ancho máximo de una imagen de salida en píxeles. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Establece el ancho máximo de una imagen de salida en píxeles. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Devuelve la altura máxima de una imagen de salida en píxeles. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Establece la altura máxima de una imagen de salida en píxeles. |
|
|  | [isExtractText()](#isExtractText--) | Determina si la extracción de texto está habilitada. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Habilita o deshabilita la extracción de texto. |
|
|  | [getWidth()](#getWidth--) | Devuelve el ancho de la imagen de salida en píxeles. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de la imagen de salida en píxeles. |
|
|  | [getHeight()](#getHeight--) | Devuelve la altura de la imagen de salida en píxeles. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de la imagen de salida en píxeles. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Obtiene la devolución de llamada para estimar el progreso de guardado de un documento. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Establece la devolución de llamada para estimar el progreso de guardado de un documento. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


Inicializa una nueva instancia de la
PngViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la
PngViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | El método que libera el flujo creado por el método asignado al parámetro createPageStream. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


Inicializa una nueva instancia de la
PngViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


Inicializa una nueva instancia de
PngViewOptions
clase.


Este constructor inicializa una nueva instancia de
PngViewOptions

con "p_{0}.png" como formato de ruta de archivo para los archivos de salida.
Los archivos de salida se colocarán en el directorio de trabajo actual de la aplicación.
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


Inicializa una nueva instancia de la
PngViewOptions
clase.


Por ejemplo, si el formato de ruta de archivo es 'page_{0}.png', los archivos de salida serán
nombrados como 'page_1.png', 'page_2.png', y así sucesivamente, según el número de página.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej., 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


Inicializa una nueva instancia de la
PngViewOptions
clase.


Por ejemplo, si el formato de ruta de archivo es 'page_{0}.png', los archivos de salida serán
nombrados como 'page_1.png', 'page_2.png', y así sucesivamente, según el número de página.
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | El formato de ruta de archivo, p. ej., 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Devuelve el ancho máximo de una imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - el ancho máximo de la imagen de salida.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Establece el ancho máximo de una imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxWidth | int | El ancho máximo de la imagen de salida. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Devuelve la altura máxima de una imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - la altura máxima de la imagen de salida.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Establece la altura máxima de una imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxHeight | int | La altura máxima de la imagen de salida. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Determina si la extracción de texto está habilitada.


Esta opción podría ser útil cuando desea agregar una capa de texto seleccionable sobre la imagen.
Utilice esta propiedad para obtener el texto contenido en un documento fuente y sus coordenadas. Luego puede usar estos datos para agregar un texto seleccionable sobre la imagen o para implementar una búsqueda de texto en la renderización basada en imágenes.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  si la extracción de texto está habilitada,  false  de lo contrario.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Habilita o deshabilita la extracción de texto.


Esta opción podría ser útil cuando desea agregar una capa de texto seleccionable sobre la imagen.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar la extracción de texto,  false  para deshabilitarla. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Devuelve el ancho de la imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - el ancho de la imagen de salida.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de la imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de la imagen de salida. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Devuelve la altura de la imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - la altura de la imagen de salida.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de la imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura de la imagen de salida. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Obtiene la devolución de llamada para estimar el progreso de guardado de un documento.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - la devolución de llamada para estimar el progreso de guardado del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Establece la devolución de llamada para estimar el progreso de guardado de un documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | La devolución de llamada para estimar el progreso de guardado del documento. |
|

