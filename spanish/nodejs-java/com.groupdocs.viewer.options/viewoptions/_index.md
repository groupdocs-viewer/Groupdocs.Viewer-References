---
title: "ViewOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Contiene las opciones de renderizado."
type: docs
weight: 35
url: /es/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

Contiene las opciones de renderizado.

La clase ViewOptions extiende la clase BaseViewOptions y sirve como clase base para las opciones de renderizado en el componente GroupDocs.Viewer. Encapsula configuraciones y parámetros comunes que pueden usarse para renderizar varios tipos de documentos en diferentes formatos.

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWatermark()](#getWatermark--) | Obtiene la marca de agua de texto aplicada a cada página. |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | Establece la marca de agua de texto que se aplicará a cada página. |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | Aplica una rotación en sentido horario a la página especificada. |
| [getPageRotations()](#getPageRotations--) | Recupera las rotaciones de página. |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | Para evitar crear la instancia solo para comprobar que está vacía |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


Obtiene la marca de agua de texto aplicada a cada página.

En caso de que tanto \#setWatermark(Watermark).setWatermark(Watermark) como \#getPageRotations().getPageRotations() estén especificados, la marca de agua se aplicará a las páginas rotadas. Para más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


Establece la marca de agua de texto que se aplicará a cada página.

En caso de que tanto  ViewOptions.Watermark  como \#getPageRotations().getPageRotations() estén especificados, la marca de agua se aplicará a las páginas rotadas. Para más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | La marca de agua de texto a establecer. |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


Aplica una rotación en sentido horario a la página especificada.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber | int | El número de página debe ser estrictamente mayor que 0. |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | El valor de rotación. |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


Recupera las rotaciones de página.

Si tanto [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) como getPageRotations() están especificados, la marca de agua se aplicará a las páginas rotadas. Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - un mapa que contiene los números de página como claves y sus rotaciones correspondientes como valores.
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


Para evitar crear la instancia solo para comprobar que está vacía

**Returns:**
boolean
