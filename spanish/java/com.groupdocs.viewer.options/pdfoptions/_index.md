---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar documentos PDF."
type: docs
weight: 22
url: /es/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Proporciona opciones para renderizar documentos PDF.


La clase PdfOptions encapsula varios ajustes y parámetros que pueden usarse
para controlar la renderización de documentos PDF en el componente GroupDocs.Viewer.
Para más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


Ejemplo de uso:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | Inicializa una nueva instancia de |
PdfOptions
clase.
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | Desactiva la protección contra copia de contenido al renderizar a HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Desactiva la protección contra copia de contenido al renderizar a HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | Determina si el texto de la fuente se renderiza como una imagen en HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Establece si el texto de la fuente se renderiza como una imagen en HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Comprueba si la agrupación de caracteres está desactivada para mantener la máxima precisión durante la posición de los caracteres al renderizar la página. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Establece la opción de desactivar la agrupación de caracteres, asegurando la máxima precisión durante la posición de los caracteres al renderizar la página. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Comprueba si la renderización de texto y gráficos debe seguir el orden Z en el documento PDF original al renderizar a HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Habilita o deshabilita la representación de texto y gráficos según el orden z en el documento PDF original al renderizar a HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | Determina si la mejora de fuentes está habilitada. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Habilita la mejora de fuentes. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Habilita la representación de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF de origen. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Habilita la representación de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF de origen. |
|
|  | [getImageQuality()](#getImageQuality--) | Obtiene la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Establece la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF es un formato fijo, por lo que todos los elementos tienen una posición específica en una página. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF es un formato fijo, por lo que todos los elementos tienen una posición específica en una página. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Active esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG y mejorar la calidad de salida. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Active esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG y mejorar la calidad de salida. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Deshabilita cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Establezca la bandera para deshabilitar cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Inicializa una nueva instancia de
PdfOptions
clase.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Desactiva la protección contra copia de contenido al renderizar a HTML.


Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML 'inert' a la etiqueta BODY del HTML.
El valor predeterminado de esta opción es
false
.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Desactiva la protección contra copia de contenido al renderizar a HTML.


Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML 'inert' a la etiqueta BODY del HTML.
El valor predeterminado de esta opción es
false
.


Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Determina si el texto de la fuente se renderiza como una imagen en HTML.


Cuando esta opción se establece en
true
, el texto se representa como una imagen en el HTML de salida.
Active esta opción para que el texto no sea seleccionable o para corregir la representación de caracteres y hacer que el HTML se asemeje al PDF.
Esta opción es compatible al renderizar a HTML.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  si el texto se representa como una imagen en HTML,  false  de lo contrario.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Establece si el texto de la fuente se renderiza como una imagen en HTML.


Cuando esta opción se establece en
true
, el texto se representa como una imagen en el HTML de salida.
Active esta opción para que el texto no sea seleccionable o para corregir la representación de caracteres y hacer que el HTML se asemeje al PDF.
Esta opción es compatible al renderizar a HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  para renderizar el texto como una imagen en HTML,  false  de lo contrario. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Comprueba si la agrupación de caracteres está desactivada para mantener la máxima precisión durante la posición de los caracteres al renderizar la página.
Cuando esta opción está habilitada, los caracteres se renderizan sin ningún agrupamiento, lo que garantiza la máxima precisión.


***Note:** By default, character grouping is enabled.*
Al convertir archivos PDF, GroupDocs.Viewer agrupa caracteres individuales en palabras para mejorar el rendimiento de renderizado. Si su documento incluye jeroglíficos o símbolos especiales, puede que desee prohibir el agrupamiento de caracteres para garantizar un diseño más preciso. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  si el agrupamiento de caracteres está deshabilitado,  false  de lo contrario.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Establece la opción de desactivar la agrupación de caracteres, asegurando la máxima precisión durante la posición de los caracteres al renderizar la página.
Cuando esta opción está habilitada estableciendo el valor a
true
, el agrupamiento de caracteres está deshabilitado, lo que garantiza la máxima precisión.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
Al convertir archivos PDF, GroupDocs.Viewer agrupa caracteres individuales en palabras para mejorar el rendimiento de renderizado. Si su documento incluye jeroglíficos o símbolos especiales, puede que desee prohibir el agrupamiento de caracteres para garantizar un diseño más preciso. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para desactivar el agrupamiento de caracteres,  false  para activarlo. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Comprueba si la renderización de texto y gráficos debe seguir el orden Z en el documento PDF original al renderizar a HTML.
Cuando esta opción está habilitada devolviendo
true
, el texto y los gráficos se renderizan de acuerdo con su orden z en el documento PDF original.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Por defecto, GroupDocs.Veiewer renderiza texto y gráficos como una sola capa en HTML. Esta opción le permite organizar los objetos en el mismo orden que en el archivo fuente. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  si el renderizado en capas está habilitado,  false  de lo contrario.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Habilita o deshabilita la representación de texto y gráficos según el orden z en el documento PDF original al renderizar a HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
Por defecto, GroupDocs.Veiewer renderiza texto y gráficos como una sola capa en HTML. Esta opción le permite organizar los objetos en el mismo orden que en el archivo fuente. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar el renderizado en capas,  false  para deshabilitarlo. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Determina si el ajuste de fuentes está habilitado. El ajuste de fuentes ajusta la visualización de una fuente de contorno.
Esta opción solo es compatible con fuentes TrueType (TTF) cuando se usan en el documento fuente.


***Note:** This option is supported when rendering into PNG or JPG formats.*
El ajuste de fuentes modifica cómo se muestra una fuente de contorno. Solo aplicable a fuentes TTF usadas en el documento fuente. Esta opción está disponible para renderizar a formatos PNG o JPG. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  si el ajuste de fuentes está habilitado,  false  de lo contrario.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Habilita el ajuste de fuentes. El ajuste de fuentes ajusta la visualización de una fuente de contorno y solo es compatible con fuentes TrueType (TTF) cuando se usan en el documento fuente.


***Note:** This option is supported when rendering into PNG or JPG formats.*
El ajuste de fuentes modifica cómo se muestra una fuente de contorno. Solo aplicable a fuentes TTF usadas en el documento fuente. Esta opción está disponible para renderizar a formatos PNG o JPG. El valor predeterminado es false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | boolean | true  para habilitar el ajuste de fuentes,  false  para deshabilitarlo. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Habilita la representación de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF de origen.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Por defecto, GroupDocs.Viewer calcula el tamaño de página de la imagen de salida para una mejor calidad de renderizado. Habilite esta opción para garantizar que las páginas de salida tengan el mismo tamaño que el tamaño de página del documento PDF fuente (en píxeles). El valor predeterminado es false.
Esta opción está disponible para renderizar a formatos PNG o JPG.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  si la opción está habilitada,  false  de lo contrario.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Habilita la representación de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF de origen.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
Por defecto, GroupDocs.Viewer calcula el tamaño de página de la imagen de salida para una mejor calidad de renderizado. Habilite esta opción para garantizar que las páginas de salida tengan el mismo tamaño que el tamaño de página del documento PDF fuente (en píxeles). El valor predeterminado es false.
Esta opción está disponible para renderizar a formatos PNG o JPG.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  para habilitar la renderización con el tamaño de página original,  false  de lo contrario. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Recupera la calidad de imagen de salida para los recursos de imagen al renderizar en HTML. El valor predeterminado es Low.


Cuando esta opción se establece en true, GroupDocs.Viewer renderiza el texto como una imagen en la salida HTML. Esto hace que el texto no sea seleccionable y mejora la renderización de caracteres, garantizando una apariencia similar a PDF en HTML. El valor predeterminado es false.
Esta opción está disponible para renderizar a HTML.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Establece la calidad de imagen de salida para los recursos de imagen al renderizar en HTML. El valor predeterminado es Low.


Cuando esta opción se establece en true, GroupDocs.Viewer renderiza el texto como una imagen en la salida HTML. Esto hace que el texto no sea seleccionable y mejora la renderización de caracteres, garantizando una apariencia similar a PDF en HTML. El valor predeterminado es false.
Esta opción está disponible para renderizar a HTML.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | La calidad de imagen de salida para los recursos de imagen al renderizar en HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF es un formato fijo, por lo que todos los elementos tienen una posición específica en una página.
Para garantizar que el HTML de salida se vea igual que el PDF original, los documentos se renderizan a HTML con un diseño fijo de forma predeterminada.
Al renderizar con diseño fijo, el HTML de salida tiene un tamaño fijo, por lo que los elementos permanecerán en el mismo lugar sin importar el tamaño de la ventana.
Para renderizar a HTML con diseño fluido, establezca esta propiedad en false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Los documentos PDF y EPUB se renderizan inicialmente a HTML con un diseño fijo para mantener la apariencia del documento original. Este diseño fijo significa que todos los elementos HTML tienen posiciones precisas dentro de un contenedor con un tamaño establecido. Cambiar el tamaño de la ventana del navegador no afecta la posición y el tamaño de los elementos en el documento.
Esta opción solo está disponible al renderizar a HTML. El valor predeterminado es true. Para renderizar con un diseño fluido, establezca esta propiedad en false.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - true si es un diseño fijo

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF es un formato fijo, por lo que todos los elementos tienen una posición específica en una página.
Para garantizar que el HTML de salida se vea igual que el PDF original, los documentos se renderizan a HTML con un diseño fijo de forma predeterminada.
Al renderizar con diseño fijo, el HTML de salida tiene un tamaño fijo, por lo que los elementos permanecerán en el mismo lugar sin importar el tamaño de la ventana.
Para renderizar a HTML con diseño fluido, establezca esta propiedad en false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
Los documentos PDF y EPUB se renderizan inicialmente a HTML con un diseño fijo para mantener la apariencia del documento original. Este diseño fijo significa que todos los elementos HTML tienen posiciones precisas dentro de un contenedor con un tamaño establecido. Cambiar el tamaño de la ventana del navegador no afecta la posición y el tamaño de los elementos en el documento.
Esta opción solo está disponible al renderizar a HTML. El valor predeterminado es true. Para renderizar con un diseño fluido, establezca esta propiedad en false.


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | fixedLayout | boolean | true si es un diseño fijo |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Active esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG y mejorar la calidad de salida.


Esta opción es compatible al renderizar [formatos de archivo PDF y Page Layout](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) a HTML con recursos incrustados y externos.


De forma predeterminada, al renderizar a archivos PDF y Page Layout, todas las imágenes se renderizan como una sola imagen PNG. La imagen PNG renderizada se utiliza como fondo para el documento HTML de salida.


Aprende más:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  si las imágenes están envueltas en SVG,  false  de lo contrario.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Active esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG y mejorar la calidad de salida.


Esta opción es compatible al renderizar [formatos de archivo PDF y Page Layout](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) a HTML con recursos incrustados y externos.


De forma predeterminada, al renderizar a archivos PDF y Page Layout, todas las imágenes se renderizan como una sola imagen PNG. La imagen PNG renderizada se utiliza como fondo para el documento HTML de salida.


Aprende más:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  si las imágenes deben estar envueltas en SVG,  false  de lo contrario. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | analyzeFonts | boolean | true si las fuentes deben mostrarse, false de lo contrario. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Deshabilita cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.


Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.
Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación de esta fuente.
Tenga cuidado al usar esta bandera. Cuando está establecida, significa que la persona que la establece asume toda la responsabilidad
por posibles violaciones de licencia/ley por su cuenta. Por lo tanto, lo hacen bajo su propio riesgo. Se recomienda encarecidamente usar
esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto, false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Establezca la bandera para deshabilitar cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.


Muchas operaciones con la fuente no pueden ejecutarse si estas operaciones están prohibidas por la licencia de esta fuente.
Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación de esta fuente.
Tenga cuidado al usar esta bandera. Cuando está establecida, significa que la persona que la establece asume toda la responsabilidad
por posibles violaciones de licencia/ley por su cuenta. Por lo tanto, lo hacen bajo su propio riesgo. Se recomienda encarecidamente usar
esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. Por defecto, false.
Para un ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


Ejemplo de uso:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

