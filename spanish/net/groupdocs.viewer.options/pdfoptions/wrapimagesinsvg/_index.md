---
title: "WrapImagesInSvg"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Habilita envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad del resultado."
type: docs
weight: 110
url: /es/net/groupdocs.viewer.options/pdfoptions/wrapimagesinsvg/
---

## PdfOptions.WrapImagesInSvg property

Habilita envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad del resultado.

```csharp
public bool WrapImagesInSvg { get; set; }
```

### Observaciones

Por defecto, al renderizar archivos PDF y de diseño de página a HTML, todas las imágenes se renderizan como una única imagen PNG. La imagen PNG renderizada se usa como fondo del documento HTML de salida.

Esta opción está disponible al renderizar [formatos de archivo PDF y de diseño de página](https://docs.groupdocs.com/viewer/net/supported-document-formats/#pdf-and-page-layout-file-formats) a HTML con recursos incrustados y externos. Permite envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG. El valor predeterminado es `false`.

Para un ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/#enclose-images-in-svg-when-rendering-pdf-and-page-layout-files).

### Ver también

* class [PdfOptions](../../pdfoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
