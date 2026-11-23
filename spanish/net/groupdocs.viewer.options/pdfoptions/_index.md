---
title: "PdfOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar documentos PDF. Para más detalles, consulte la documentaciónhttps//docs.groupdocs.com/viewer/net/renderpdfdocuments/."
type: docs
weight: 410
url: /es/net/groupdocs.viewer.options/pdfoptions/
---

## PdfOptions class

Contiene opciones para renderizar documentos PDF. Para más detalles, consulte la [documentación](https://docs.groupdocs.com/viewer/net/render-pdf-documents/).

```csharp
public class PdfOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfOptions](pdfoptions)() | Inicializa una nueva instancia de la clase [`PdfOptions`](../pdfoptions). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [DisableCharsGrouping](../../groupdocs.viewer.options/pdfoptions/disablecharsgrouping) { get; set; } | Desactiva la agrupación de símbolos para un posicionamiento preciso de los símbolos durante el renderizado de la página. |
| [DisableCopyProtection](../../groupdocs.viewer.options/pdfoptions/disablecopyprotection) { get; set; } | Desactiva la protección contra copia de contenido al renderizar a HTML. |
| [DisableFontLicenseVerifications](../../groupdocs.viewer.options/pdfoptions/disablefontlicenseverifications) { get; set; } | Desactiva cualquier restricción de licencia para todas las fuentes en el documento XPS/OXPS actual. |
| [EnableFontHinting](../../groupdocs.viewer.options/pdfoptions/enablefonthinting) { get; set; } | Habilita el hinting de fuentes. |
| [EnableLayeredRendering](../../groupdocs.viewer.options/pdfoptions/enablelayeredrendering) { get; set; } | Habilita el renderizado de texto y gráficos en el orden Z del documento PDF original al renderizar a HTML. |
| [FixedLayout](../../groupdocs.viewer.options/pdfoptions/fixedlayout) { get; set; } | Habilita el renderizado de los documentos PDF y EPUB a HTML con un diseño fijo. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptions/imagequality) { get; set; } | Establece la calidad de imagen de salida para los recursos de imagen al renderizar a HTML. La calidad predeterminada es `Low`. |
| [RenderOriginalPageSize](../../groupdocs.viewer.options/pdfoptions/renderoriginalpagesize) { get; set; } | Establece el tamaño de página de salida igual al tamaño de página del documento PDF fuente. |
| [RenderTextAsImage](../../groupdocs.viewer.options/pdfoptions/rendertextasimage) { get; set; } | Habilita el renderizado de textos en los archivos PDF como una imagen en la salida HTML. |
| [WrapImagesInSvg](../../groupdocs.viewer.options/pdfoptions/wrapimagesinsvg) { get; set; } | Habilita envolver cada imagen en el documento HTML de salida dentro de una etiqueta SVG para mejorar la calidad del resultado. |

### Ver también

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
