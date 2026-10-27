---
title: "ImageQuality"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "La calidad de las imágenes en el HTML de salida contenido por los documentos PDF."
type: docs
weight: 41
url: /es/nodejs-java/com.groupdocs.viewer.options/imagequality/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum ImageQuality extends Enum<ImageQuality>
```

La calidad de las imágenes en el HTML de salida contenido por los documentos PDF.

El enum ImageQuality representa la calidad de las imágenes en el HTML de salida contenido por los documentos PDF en el componente GroupDocs.Viewer. Proporciona diferentes niveles de calidad de imagen que pueden usarse para controlar la renderización y compresión de imágenes en el HTML generado.

Ejemplo de uso:

```

 HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 PdfOptions pdfOptions = htmlViewOptions.getPdfOptions();
 pdfOptions.setImageQuality(ImageQuality.HIGH);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
```
## Fields

| Field | Descripción |
| --- | --- |
| [LOW](#LOW) | La calidad aceptable y el mejor rendimiento. |
| [MEDIUM](#MEDIUM) | Mejor calidad y rendimiento más lento. |
| [HIGH](#HIGH) | La mejor calidad pero rendimiento lento. |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### LOW {#LOW}
```
public static final ImageQuality LOW
```


La calidad aceptable y el mejor rendimiento. Esta configuración prioriza la velocidad de renderizado sobre la calidad de la imagen.

### MEDIUM {#MEDIUM}
```
public static final ImageQuality MEDIUM
```


Mejor calidad y rendimiento más lento. Esta configuración ofrece un equilibrio entre la calidad de la imagen y la velocidad de renderizado.

### HIGH {#HIGH}
```
public static final ImageQuality HIGH
```


La mejor calidad pero rendimiento lento. Esta configuración prioriza la calidad de la imagen sobre la velocidad de renderizado.

### values() {#values--}
```
public static ImageQuality[] values()
```




**Returns:**
com.groupdocs.viewer.options.ImageQuality[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static ImageQuality valueOf(String name)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality)
