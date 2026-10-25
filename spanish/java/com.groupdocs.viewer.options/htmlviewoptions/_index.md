---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos en formato HTML."
type: docs
weight: 16
url: /es/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

Proporciona opciones para renderizar documentos en formato HTML.


La clase HtmlViewOptions encapsula configuraciones y parámetros adicionales
que pueden usarse para controlar la renderización de documentos en formato HTML en el componente GroupDocs.Viewer.


Para obtener más detalles, consulte el [tema](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) y sus elementos secundarios.


Ejemplo de uso:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## Campos

| Campo | Descripción |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | Determina si la renderización responsiva está habilitada. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | Establece si la renderización responsiva está habilitada. |
|
|  | [isMinify()](#isMinify--) | Comprueba si la minificación de contenido HTML y recursos HTML está habilitada. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | Establece si la minificación de contenido HTML y recursos HTML está habilitada. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | Habilita la renderización de todo un documento en un solo archivo HTML. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | Habilita la renderización de todo un documento en un solo archivo HTML. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | Devuelve el ancho máximo de una imagen de salida en píxeles. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | Establece el ancho máximo de una imagen de salida en píxeles. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | Obtiene la altura máxima de una imagen de salida en píxeles. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | Establece la altura máxima de una imagen de salida en píxeles. |
|
|  | [getImageWidth()](#getImageWidth--) | Obtiene el ancho de la imagen de salida en píxeles. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | Establece el ancho de la imagen de salida en píxeles. |
|
|  | [getImageHeight()](#getImageHeight--) | Obtiene la altura de la imagen de salida en píxeles al convertir una sola imagen a HTML. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | Establece la altura de la imagen de salida en píxeles al convertir una sola imagen a HTML. |
|
|  | [isForPrinting()](#isForPrinting--) | Comprueba si el HTML de salida debe optimizarse para impresión. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | Establece si el HTML de salida debe optimizarse para impresión. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | Determina si excluir fuentes del documento HTML. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | Establece si se excluyen fuentes del documento HTML. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | Obtiene la lista de nombres de fuentes a excluir del documento HTML. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | Establece la lista de nombres de fuentes a excluir del documento HTML. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | Permite eliminar el código fuente JavaScript de los enlaces en los documentos HTML resultantes, al renderizar documentos de entrada que contienen scripts. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | Establece el permiso para eliminar el código fuente JavaScript de los enlaces en los documentos HTML resultantes, al renderizar documentos de entrada que contienen scripts. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | Obtiene la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | Establece la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos externos.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos externos.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase para renderizar en HTML con recursos externos.
|
|  | [forExternalResources()](#forExternalResources--) | Inicializa una nueva instancia de |
HtmlViewOptions
clase.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | Inicializa una nueva instancia de la |
HtmlViewOptions
clase.
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


Determina si la renderización responsiva está habilitada.
Las páginas web responsivas se renderizan bien en dispositivos con diferentes tamaños de pantalla.


El diseño responsivo tiene como objetivo que las páginas web se rendericen bien en una variedad de dispositivos. Para renderizar con un diseño responsivo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Returns:**
boolean -  true  si el renderizado responsivo está habilitado,  false  en caso contrario.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


Establece si la renderización responsiva está habilitada.
Las páginas web responsivas se renderizan bien en dispositivos con diferentes tamaños de pantalla.


El diseño responsivo tiene como objetivo que las páginas web se rendericen bien en una variedad de dispositivos. Para renderizar con un diseño responsivo, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar el renderizado responsivo,  false  para deshabilitarlo. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


Comprueba si la minificación de contenido HTML y recursos HTML está habilitada.


La compresión del contenido de salida (HTML, CSS y SVG) es una de las formas de optimizar el archivo HTML. Para ello, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Returns:**
boolean -  true  si la minificación está habilitada,  false  en caso contrario.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


Establece si la minificación de contenido HTML y recursos HTML está habilitada.


La compresión del contenido de salida (HTML, CSS y SVG) es una de las formas de optimizar el archivo HTML. Para ello, establezca esta propiedad en true.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar la minificación,  false  para deshabilitarla. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


Habilita la renderización de todo un documento en un solo archivo HTML.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


Habilita la renderización de todo un documento en un solo archivo HTML.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


Devuelve el ancho máximo de una imagen de salida en píxeles.
***Note:** This value is used when converting a single image to HTML.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - el ancho máximo de una imagen de salida.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


Establece el ancho máximo de una imagen de salida en píxeles.
***Note:** This value is used when converting a single image to HTML.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageMaxWidth | int | El ancho máximo de una imagen de salida. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


Obtiene la altura máxima de una imagen de salida en píxeles.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - la altura máxima de una imagen de salida.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


Establece la altura máxima de una imagen de salida en píxeles.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageMaxHeight | int | La altura máxima de una imagen de salida. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


Obtiene el ancho de la imagen de salida en píxeles.


***Note:** This value is applicable only when converting a single image to HTML.*
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - el ancho de la imagen de salida.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


Establece el ancho de la imagen de salida en píxeles.


***Note:** This value is applicable only when converting a single image to HTML.*
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageWidth | int | El ancho de la imagen de salida. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


Obtiene la altura de la imagen de salida en píxeles al convertir una sola imagen a HTML.


Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - la altura de la imagen de salida en píxeles.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


Establece la altura de la imagen de salida en píxeles al convertir una sola imagen a HTML.


Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | imageHeight | int | La altura de la imagen de salida en píxeles. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


Comprueba si el HTML de salida debe optimizarse para impresión.


Active esta opción para convertir las páginas HTML de salida al formato vectorial SVG.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  si el HTML de salida debe optimizarse para impresión,  false  en caso contrario.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


Establece si el HTML de salida debe optimizarse para impresión.


Active esta opción para convertir las páginas HTML de salida al formato vectorial SVG.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para optimizar el HTML de salida para impresión,  false  en caso contrario. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


Determina si excluir fuentes del documento HTML.


De forma predeterminada, GroupDocs.Viewer incrusta las fuentes utilizadas en el documento en HTML. Para evitarlo, establezca esta propiedad en true.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  si las fuentes deben excluirse,  false  en caso contrario.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


Establece si se excluyen fuentes del documento HTML.


De forma predeterminada, GroupDocs.Viewer incrusta las fuentes utilizadas en el documento en HTML. Para evitarlo, establezca esta propiedad en true.
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para excluir fuentes,  false  en caso contrario. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


Obtiene la lista de nombres de fuentes a excluir del documento HTML.


Esta opción solo es compatible con presentaciones.
Incluir fuentes en el documento HTML mejora la estabilidad de la vista de salida pero aumenta el tamaño del resultado del renderizado.
Utilice esta opción para encontrar un compromiso entre la estabilidad y el tamaño de salida.
Incluya nombres de fuentes que sean populares y estén instalados en la mayoría de los sistemas.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) la opción está deshabilitada.*
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> - la lista de nombres de fuentes a excluir del documento HTML.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


Establece la lista de nombres de fuentes a excluir del documento HTML.


Esta opción solo es compatible con presentaciones.
Incluir fuentes en el documento HTML mejora la estabilidad de la vista de salida pero aumenta el tamaño del resultado del renderizado.
Utilice esta opción para encontrar un compromiso entre la estabilidad y el tamaño de salida.
Incluya nombres de fuentes que sean populares y estén instalados en la mayoría de los sistemas.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) la opción está deshabilitada.*
Para obtener más detalles y un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.util.List<java.lang.String> | La lista de nombres de fuentes a excluir del documento HTML. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


Permite eliminar el código fuente JavaScript de los enlaces en los documentos HTML resultantes, al renderizar documentos de entrada que contienen scripts. Por defecto está habilitado (true).


Para obtener detalles sobre la eliminación de JavaScript, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


Establece el permiso para eliminar el código fuente JavaScript de los enlaces en los documentos HTML resultantes, al renderizar documentos de entrada que contienen scripts. Por defecto está habilitado (true).


Para obtener detalles sobre la eliminación de JavaScript, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


Obtiene la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - la devolución de llamada utilizada para estimar el progreso de guardado del documento.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


Establece la devolución de llamada utilizada para estimar el progreso de guardado de un documento Words o Email.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | La devolución de llamada utilizada para estimar el progreso de guardado del documento. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.


***Note:** The method takes a 
CreatePageStream
parámetro, que es un método utilizado para instanciar un flujo para escribir datos de página de salida.*
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia un flujo utilizado para escribir datos de página de salida. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia un flujo utilizado para escribir datos de página de salida. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | El método que libera el flujo creado por el método asignado al  createPageStream  parámetro. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos incrustados.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej., 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | El formato de ruta de archivo, p. ej., 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos externos.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir datos de página de salida. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | El método que libera el flujo creado por el método  createPageStream . |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | El método que crea la URL para el recurso HTML. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos externos.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | El método que instancia el flujo utilizado para escribir datos de página de salida. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | El método que instancia el flujo utilizado para escribir datos del recurso HTML de salida. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | El método que crea la URL para el recurso HTML. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | El método que libera el flujo creado por el método  createPageStream . |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | El método que libera el flujo creado por el método  createResourceStream . |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase para renderizar en HTML con recursos externos.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | La fábrica que implementa métodos para crear URLs de recursos y para instanciar/liberar el flujo de recurso HTML de salida. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


Inicializa una nueva instancia de
HtmlViewOptions
clase.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

Los archivos de salida se colocarán en el directorio de trabajo actual de la aplicación. Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


Inicializa una nueva instancia de la
HtmlViewOptions
clase.


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | El formato de ruta de archivo, p. ej., 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | El formato de ruta de archivo de recurso, p. ej., 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | El formato de URL de recurso, p. ej., 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
