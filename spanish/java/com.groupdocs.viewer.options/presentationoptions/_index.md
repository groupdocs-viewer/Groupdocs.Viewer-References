---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Java Referencia de API"
description: "Proporciona opciones para renderizar presentaciones."
type: docs
weight: 26
url: /es/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Proporciona opciones para renderizar presentaciones.


Para obtener más detalles, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | Habilita un nuevo modo de renderizado HTML para documentos de Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Habilita un nuevo modo de renderizado HTML para documentos de Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | Habilita la renderización de marcadores de posición en el encabezado y pie de diapositiva. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | Habilita la renderización de marcadores de posición en el encabezado y pie de diapositiva. |
|
|  | [getResolution()](#getResolution--) | Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Habilita un nuevo modo de renderizado HTML para documentos de Presentation.


En este modo, los archivos Presentation se renderizan a marcado HTML/CSS puro, sin imágenes SVG.
Por defecto, esta función está deshabilitada (false). Se utiliza el renderizador HTML basado en SVG existente si esta opción no está habilitada.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Habilita un nuevo modo de renderizado HTML para documentos de Presentation.


En este modo, los archivos Presentation se renderizan a marcado HTML/CSS puro, sin imágenes SVG.
Por defecto, esta función está deshabilitada (false). Se utiliza el renderizador HTML basado en SVG existente si esta opción no está habilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


Habilita la representación de marcadores de posición en el encabezado y pie de una diapositiva. Deshabilitado por defecto (false). Esta opción se aplica a los 4 modos de renderizado de presentaciones: HTML, PDF, PNG y JPEG. No es aplicable al renderizar la presentación a marcado puro HTML/CSS usando .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


Habilita la representación de marcadores de posición en el encabezado y pie de una diapositiva. Deshabilitado por defecto (false). Esta opción se aplica a los 4 modos de renderizado de presentaciones: HTML, PDF, PNG y JPEG. No es aplicable al renderizar la presentación a marcado puro HTML/CSS usando .


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF).


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF).


Para el ejemplo de código, consulte la [documentación](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

