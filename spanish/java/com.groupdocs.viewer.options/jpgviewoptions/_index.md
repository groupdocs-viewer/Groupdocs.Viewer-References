---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos en formato JPG."
type: docs
weight: 17
url: /es/java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

Proporciona opciones para renderizar documentos en formato JPG.


La clase JpgViewOptions encapsula configuraciones y parámetros adicionales que pueden usarse para controlar el renderizado de documentos
en formato JPG en el componente GroupDocs.Viewer.


Ejemplo de uso:

````

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inicializa una nueva instancia de la |
JpgViewOptions
clase.
|
|  | [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inicializa una nueva instancia de la |
JpgViewOptions
clase.
|
|  | [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inicializa una nueva instancia de la |
JpgViewOptions
clase.
|
|  | [JpgViewOptions()](#JpgViewOptions--) | Inicializa una nueva instancia de |
JpgViewOptions
con "p_{0}.jpg" como el formato de ruta de archivo para los archivos de salida.
|
|  | [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | Inicializa una nueva instancia de la |
JpgViewOptions
clase.
|
|  | [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | Inicializa una nueva instancia de la |
JpgViewOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | Obtiene el ancho máximo de una imagen de salida en píxeles. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Establece el ancho máximo de una imagen de salida en píxeles. |
|
|  | [getMaxHeight()](#getMaxHeight--) | Obtiene la altura máxima de una imagen de salida en píxeles. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Establece la altura máxima de una imagen de salida en píxeles. |
|
|  | [getQuality()](#getQuality--) | Obtiene la calidad de la imagen de salida. |
|
|  | [setQuality(byte value)](#setQuality-byte-) | Establece la calidad de la imagen de salida. |
|
|  | [isExtractText()](#isExtractText--) | Permite la extracción de texto. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | Habilita o deshabilita la extracción de texto. |
|
|  | [getWidth()](#getWidth--) | Obtiene el ancho de la imagen de salida en píxeles. |
|
|  | [setWidth(int value)](#setWidth-int-) | Establece el ancho de la imagen de salida en píxeles. |
|
|  | [getHeight()](#getHeight--) | Obtiene la altura de la imagen de salida en píxeles. |
|
|  | [setHeight(int value)](#setHeight-int-) | Establece la altura de la imagen de salida en píxeles. |
|
|  | [getPageStreamFactory()](#getPageStreamFactory--) | Obtiene la fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Obtiene la devolución de llamada para estimar el progreso de guardado de un documento Words o Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Establece la devolución de llamada para estimar el progreso de guardado de un documento Words o Email. |
|
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


Inicializa una nueva instancia de la
JpgViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
|

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la
JpgViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | El método que libera el flujo creado por el método asignado al delegado pasado al parámetro  createPageStream . |
|

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


Inicializa una nueva instancia de la
JpgViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
|

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


Inicializa una nueva instancia de
JpgViewOptions
con "p_{0}.jpg" como el formato de ruta de archivo para los archivos de salida.
Los archivos de salida se colocarán en el directorio de trabajo actual de la aplicación.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


Inicializa una nueva instancia de la
JpgViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej., 'page_{0}.jpg'. |
|

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


Inicializa una nueva instancia de la
JpgViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | El formato de ruta de archivo, p. ej., 'page_{0}.jpg'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Obtiene el ancho máximo de una imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad #setWidth(int).setWidth(int), esta propiedad se ignora.


**Returns:**
int - el ancho máximo de una imagen de salida.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Establece el ancho máximo de una imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad #setWidth(int).setWidth(int), esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxWidth | int | El ancho máximo de una imagen de salida. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Obtiene la altura máxima de una imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad #setHeight(int).setHeight(int), esta propiedad se ignora.


**Returns:**
int - la altura máxima de una imagen de salida.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Establece la altura máxima de una imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
Si establece la propiedad #setHeight(int).setHeight(int), esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxHeight | int | La altura máxima de una imagen de salida. |
|

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


Obtiene la calidad de la imagen de salida.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Returns:**
byte - la calidad de la imagen de salida.

### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


Establece la calidad de la imagen de salida.


***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.*
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | byte | La calidad de la imagen de salida. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


Permite la extracción de texto.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  si la extracción de texto está habilitada,  false  de lo contrario.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


Habilita o deshabilita la extracción de texto.


***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.*
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar la extracción de texto,  false  para deshabilitarla. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Obtiene el ancho de la imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad #setMaxWidth(int).setMaxWidth(int) se ignora.


**Returns:**
int - el ancho de la imagen de salida.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Establece el ancho de la imagen de salida en píxeles.


Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad #setMaxWidth(int).setMaxWidth(int) se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | El ancho de la imagen de salida. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Obtiene la altura de la imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad #setMaxHeight(int).setMaxHeight(int) se ignora.


**Returns:**
int - la altura de la imagen de salida.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Establece la altura de la imagen de salida en píxeles.


Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
Si establece esta propiedad, la propiedad #setMaxHeight(int).setMaxHeight(int) se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | int | La altura de la imagen de salida. |
|

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


Obtiene la fábrica que implementa métodos para crear y liberar el flujo de página de salida.


**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Obtiene la devolución de llamada para estimar el progreso de guardado de un documento Words o Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - la devolución de llamada para estimar el progreso de guardado del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Establece la devolución de llamada para estimar el progreso de guardado de un documento Words o Email.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | La devolución de llamada para estimar el progreso de guardado del documento. |
|

