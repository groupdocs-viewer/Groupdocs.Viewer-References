---
title: "PdfOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar documentos PDF."
type: docs
weight: 22
url: /es/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

Proporciona opciones para renderizar documentos PDF.

La clase PdfOptions encapsula varios ajustes y parámetros que pueden usarse para controlar la renderización de documentos PDF en el componente GroupDocs.Viewer. Para más detalles, consulte la [documentación][].

Ejemplo de uso:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | Inicializa una nueva instancia de la clase PdfOptions. |
## Métodos

| Método | Descripción |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | Desactiva la protección contra copia de contenido al renderizar a HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | Desactiva la protección contra copia de contenido al renderizar a HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | Determina si el texto de la fuente se renderiza como una imagen en HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | Establece si el texto de la fuente se renderiza como una imagen en HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | Comprueba si la agrupación de caracteres está desactivada para mantener la máxima precisión durante el posicionamiento de caracteres al renderizar la página. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | Establece la opción de desactivar la agrupación de caracteres, garantizando la máxima precisión durante el posicionamiento de caracteres al renderizar la página. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | Comprueba si la renderización de texto y gráficos debe seguir el orden z en el documento PDF original al renderizar a HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | Habilita o deshabilita la renderización de texto y gráficos según el orden z en el documento PDF original al renderizar a HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | Determina si el font hinting está habilitado. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | Habilita el font hinting. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | Habilita la renderización de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF fuente. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | Habilita la renderización de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF fuente. |
| [getImageQuality()](#getImageQuality--) | Obtiene la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | Establece la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF es un formato fijo, por lo que todos los elementos tienen un lugar específico en una página. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF es un formato fijo, por lo que todos los elementos tienen un lugar específico en una página. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | Habilite esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad de salida. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | Habilite esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad de salida. |
| [isFixLinkIssue()](#isFixLinkIssue--) | Intenta corregir el problema cuando todo el contenido de la página HTML es un enlace. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | Intenta corregir el problema cuando todo el contenido de la página HTML es un enlace. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | Reemplaza fuentes según sea necesario para garantizar que todos los caracteres del texto se puedan mostrar. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | Desactive cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | Establezca la bandera para desactivar cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


Inicializa una nueva instancia de la clase PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


Desactiva la protección contra copia de contenido al renderizar a HTML.

Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML 'inert' a la etiqueta BODY del HTML. El valor predeterminado de esta opción es  false .

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


Desactiva la protección contra copia de contenido al renderizar a HTML.

Al renderizar archivos PDF con protección contra la copia de texto e imágenes a HTML, GroupDocs.Viewer agrega un atributo HTML 'inert' a la etiqueta BODY del HTML. El valor predeterminado de esta opción es  false .

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


Determina si el texto de la fuente se renderiza como una imagen en HTML.

Cuando esta opción se establece en  true , el texto se renderiza como una imagen en el HTML de salida. Habilite esta opción para que el texto no sea seleccionable o para corregir la renderización de caracteres y hacer que el HTML se parezca a un PDF. Esta opción es compatible al renderizar a HTML.

***Note:** The default value is  false .*

**Returns:**
boolean -  true  si el texto se renderiza como una imagen en HTML,  false  de lo contrario.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


Establece si el texto de la fuente se renderiza como una imagen en HTML.

Cuando esta opción se establece en  true , el texto se renderiza como una imagen en el HTML de salida. Habilite esta opción para que el texto no sea seleccionable o para corregir la renderización de caracteres y hacer que el HTML se parezca a un PDF. Esta opción es compatible al renderizar a HTML.

***Note:** The default value is  false .*

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderTextAsImage | boolean | true  para renderizar el texto como una imagen en HTML,  false  de lo contrario. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


Comprueba si la agrupación de caracteres está desactivada para mantener la máxima precisión durante el posicionamiento de caracteres al renderizar la página. Cuando esta opción está habilitada, los caracteres se renderizan sin ninguna agrupación, lo que garantiza la máxima precisión.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean -  true  si la agrupación de caracteres está desactivada,  false  de lo contrario.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


Establece la opción para desactivar la agrupación de caracteres, asegurando la máxima precisión durante el posicionamiento de caracteres al renderizar la página. Cuando esta opción se habilita estableciendo el valor en  true , la agrupación de caracteres se desactiva, lo que garantiza la máxima precisión.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para desactivar la agrupación de caracteres,  false  para habilitarla. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


Comprueba si la renderización de texto y gráficos debe seguir el orden z en el documento PDF original al renderizar a HTML. Cuando esta opción se habilita devolviendo  true , el texto y los gráficos se renderizan según su orden z en el documento PDF original.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean -  true  si la renderización en capas está habilitada,  false  de lo contrario.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


Habilita o deshabilita la renderización de texto y gráficos según el orden z en el documento PDF original al renderizar a HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar la renderización en capas,  false  para deshabilitarla. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


Determina si el ajuste de fuentes está habilitado. El ajuste de fuentes ajusta la visualización de una fuente de contorno. Esta opción solo es compatible con fuentes TrueType (TTF) cuando se usan en el documento fuente.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean -  true  si el ajuste de fuentes está habilitado,  false  de lo contrario.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


Habilita el ajuste de fuentes. El ajuste de fuentes ajusta la visualización de una fuente de contorno y solo es compatible con fuentes TrueType (TTF) cuando se usan en el documento fuente.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean | true  para habilitar el ajuste de fuentes,  false  para deshabilitarlo. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


Habilita la renderización de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF fuente.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean -  true  si la opción está habilitada,  false  de lo contrario.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


Habilita la renderización de páginas con el mismo tamaño en píxeles que el tamaño de página en el documento PDF fuente.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true  para habilitar la renderización con el tamaño de página original,  false  de lo contrario. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


Recupera la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. El valor predeterminado es Low.

Cuando esta opción se establece en true, GroupDocs.Viewer renderiza el texto como una imagen en la salida HTML. Esto hace que el texto no sea seleccionable y mejora la renderización de caracteres, asegurando una apariencia similar a PDF en HTML. El valor predeterminado es false. Esta opción está disponible para renderizar a HTML. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


Establece la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. El valor predeterminado es Low.

Cuando esta opción se establece en true, GroupDocs.Viewer renderiza el texto como una imagen en la salida HTML. Esto hace que el texto no sea seleccionable y mejora la renderización de caracteres, asegurando una apariencia similar a PDF en HTML. El valor predeterminado es false. Esta opción está disponible para renderizar a HTML. Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | La calidad de imagen de salida para los recursos de imagen al renderizar en HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF es un formato fijo, por lo que todos los elementos tienen un lugar específico en una página. Para garantizar que el HTML de salida se vea igual que el PDF de origen, los documentos se renderizan a HTML con un diseño fijo de forma predeterminada. Al renderizar con diseño fijo, el HTML de salida tiene un tamaño fijo, de modo que los elementos permanecerán en el mismo lugar sin importar el tamaño de la ventana. Para renderizar a HTML con diseño fluido, establezca esta propiedad en false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
boolean - true si es diseño fijo
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF es un formato fijo, por lo que todos los elementos tienen un lugar específico en una página. Para garantizar que el HTML de salida se vea igual que el PDF de origen, los documentos se renderizan a HTML con un diseño fijo de forma predeterminada. Al renderizar con diseño fijo, el HTML de salida tiene un tamaño fijo, de modo que los elementos permanecerán en el mismo lugar sin importar el tamaño de la ventana. Para renderizar a HTML con diseño fluido, establezca esta propiedad en false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixedLayout | boolean | true si es diseño fijo |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


Habilite esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad de salida.

Esta opción es compatible al renderizar [PDF and Page Layout file formats][] a HTML con recursos incrustados y externos.

De forma predeterminada, al renderizar a archivos PDF y Page Layout, todas las imágenes se renderizan como una sola imagen PNG. La imagen PNG renderizada se utiliza como fondo del documento HTML de salida.

Más información:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
boolean -  true  si las imágenes se envuelven en SVG,  false  de lo contrario.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


Habilite esta opción para envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad de salida.

Esta opción es compatible al renderizar [PDF and Page Layout file formats][] a HTML con recursos incrustados y externos.

De forma predeterminada, al renderizar a archivos PDF y Page Layout, todas las imágenes se renderizan como una sola imagen PNG. La imagen PNG renderizada se utiliza como fondo del documento HTML de salida.

Más información:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true  si las imágenes deben envolverse en SVG,  false  de lo contrario. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


Intenta corregir el problema cuando todo el contenido de la página HTML es un enlace. Funciona solo cuando el formato de entrada es PDF y el formato de salida es HTML (con recursos incrustados o externos). De forma predeterminada está deshabilitado (false). Actívelo solo cuando sepa qué y por qué lo está haciendo. Activar esta opción aumenta el tiempo de procesamiento del documento.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


Intenta corregir el problema cuando todo el contenido de la página HTML es un enlace. Funciona solo cuando el formato de entrada es PDF y el formato de salida es HTML (con recursos incrustados o externos). De forma predeterminada está deshabilitado (false). Actívelo solo cuando sepa qué y por qué lo está haciendo. Activar esta opción aumenta el tiempo de procesamiento del documento.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fixLinkIssue | boolean | true si el problema debe corregirse, false de lo contrario. |

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
| analyzeFonts | boolean | true si las fuentes deben mostrarse, false de lo contrario. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


Desactive cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.

Muchas operaciones con fuentes no pueden ejecutarse si estas operaciones están prohibidas por la licencia de la fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación de esa fuente. Tenga cuidado al usar esta bandera. Cuando está activada, significa que la persona que la activa asume toda la responsabilidad por posibles violaciones de licencia o legales. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. De forma predeterminada es false. Para un ejemplo de código, consulte la [documentation][].

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


Establezca la bandera para desactivar cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual.

Muchas operaciones con fuentes no pueden ejecutarse si estas operaciones están prohibidas por la licencia de la fuente. Por ejemplo, algunas fuentes no pueden incrustarse en un documento PDF si las reglas de la licencia deshabilitan la incrustación de esa fuente. Tenga cuidado al usar esta bandera. Cuando está activada, significa que la persona que la activa asume toda la responsabilidad por posibles violaciones de licencia o legales. Por lo tanto, lo hace bajo su propio riesgo. Se recomienda encarecidamente usar esta bandera solo cuando esté completamente seguro de que no está infringiendo la ley de derechos de autor. De forma predeterminada es false. Para un ejemplo de código, consulte la [documentation][].

Ejemplo de uso:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

