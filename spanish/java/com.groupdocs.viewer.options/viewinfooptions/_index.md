---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones utilizadas para obtener información sobre la vista."
type: docs
weight: 34
url: /es/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

Proporciona opciones utilizadas para obtener información sobre la vista.


La clase ViewInfoOptions encapsula configuraciones y parámetros adicionales que
pueden usarse para obtener información sobre una vista en el componente GroupDocs.Viewer.


Ejemplo de uso:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## Métodos

| Método | Descripción |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | Indica si la extracción de texto está habilitada. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | Establece la bandera que indica si la extracción de texto está habilitada. |
|
|  | [getMaxWidth()](#getMaxWidth--) | Devuelve el ancho máximo de la imagen de salida para renderizar a PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | Establece el ancho máximo de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [getMaxHeight()](#getMaxHeight--) | Devuelve la altura máxima de la imagen de salida para renderizar a PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | Establece la altura máxima de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [getWidth()](#getWidth--) | El ancho de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [setWidth(int width)](#setWidth-int-) | El ancho de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [getHeight()](#getHeight--) | La altura de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [setHeight(int height)](#setHeight-int-) | La altura de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
|
|  | [forHtmlView()](#forHtmlView--) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en HTML.
|
|  | [forJpgView()](#forJpgView--) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en JPG.
|
|  | [forPngView()](#forPngView--) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en PNG.
|
|  | [forPdfView()](#forPdfView--) | Inicializa una nueva instancia de la clase ViewInfoOptions para obtener información sobre la vista al renderizar en PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase basada en el objeto [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase basada en el objeto [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | Inicializa una nueva instancia de la |
ViewInfoOptions
Clase basada en el objeto [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | Inicializa una nueva instancia de la clase [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basada en un objeto PdfViewOptions. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


Indica si la extracción de texto está habilitada.
Utilice esta propiedad para obtener el texto contenido en un documento fuente y sus coordenadas. Luego puede usar estos datos para agregar texto seleccionable sobre la imagen o para implementar una búsqueda de texto en renderizado basado en imágenes. Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - Verdadero si la extracción de texto está habilitada, falso en caso contrario.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


Establece la bandera que indica si la extracción de texto está habilitada.
Utilice esta propiedad para obtener el texto contenido en un documento fuente y sus coordenadas. Luego puede usar estos datos para agregar texto seleccionable sobre la imagen o para implementar una búsqueda de texto en renderizado basado en imágenes. Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extractText | boolean | Verdadero para habilitar la extracción de texto, falso para deshabilitarla. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


Devuelve el ancho máximo de la imagen de salida para renderizar a PNG/JPG.
Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - el ancho máximo de la imagen de salida.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


Establece el ancho máximo de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer el ancho máximo de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxWidth | int | El ancho máximo de la imagen de salida. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


Devuelve la altura máxima de la imagen de salida para renderizar a PNG/JPG.
Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Si establece la propiedad, esta propiedad se ignora.


**Returns:**
int - la altura máxima de la imagen de salida.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


Establece la altura máxima de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer la altura máxima de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). Si establece la propiedad, esta propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | maxHeight | int | La altura máxima de la imagen de salida. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


El ancho de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - el ancho de la imagen.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


El ancho de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer el ancho de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Si establece esta propiedad, la propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | width | int | El ancho de la imagen. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


La altura de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Si establece esta propiedad, la propiedad se ignora.


**Returns:**
int - la altura de la imagen.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


La altura de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG).
Utilice esta propiedad para establecer la altura de la imagen de salida (en píxeles). Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). Si establece esta propiedad, la propiedad se ignora.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | altura | int | La altura de la imagen. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | renderSinglePage | boolean | Permite que el contenido HTML se renderice en una sola página. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en JPG.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extractText | boolean | Permite la extracción de texto. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase para obtener información sobre la vista al renderizar en PNG.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | extractText | boolean | Permite la extracción de texto. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


Inicializa una nueva instancia de la clase ViewInfoOptions para obtener información sobre la vista al renderizar en PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase basada en el objeto [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | Las opciones de vista HTML. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase basada en el objeto [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | Las opciones de vista PNG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


Inicializa una nueva instancia de la
ViewInfoOptions
Clase basada en el objeto [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | Las opciones de vista JPG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


Inicializa una nueva instancia de la clase [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) basada en un objeto PdfViewOptions.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | Las opciones de vista PDF. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

