---
title: "PresentationOptions"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "Proporciona opciones para renderizar presentaciones."
type: docs
weight: 26
url: /es/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

Proporciona opciones para renderizar presentaciones.

Para obtener más detalles, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Habilita un nuevo modo de renderizado HTML para documentos Presentation. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Habilita un nuevo modo de renderizado HTML para documentos Presentation. |
| [getResolution()](#getResolution--) | Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Habilita un nuevo modo de renderizado HTML para documentos Presentation.

En este modo, los archivos Presentation se renderizan a marcado HTML/CSS puro, sin imágenes SVG. De forma predeterminada, esta función está deshabilitada (false). Se utiliza el renderizador HTML basado en SVG existente si esta opción no está habilitada.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Habilita un nuevo modo de renderizado HTML para documentos Presentation.

En este modo, los archivos Presentation se renderizan a marcado HTML/CSS puro, sin imágenes SVG. De forma predeterminada, esta función está deshabilitada (false). Se utiliza el renderizador HTML basado en SVG existente si esta opción no está habilitada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF).

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


Resolución para imágenes dentro de la presentación (solo para renderizado a HTML/PDF).

Para un ejemplo de código, consulte la [documentación][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

