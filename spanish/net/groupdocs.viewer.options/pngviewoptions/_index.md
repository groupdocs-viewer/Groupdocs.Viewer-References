---
title: PngViewOptions
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Proporciona opciones para representar documentos en formato PNG.
type: docs
weight: 440
url: /es/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Proporciona opciones para representar documentos en formato PNG.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Inicializa una nueva instancia de[`PngViewOptions`](../pngviewoptions) clase. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Inicializa una nueva instancia de[`PngViewOptions`](../pngviewoptions) clase. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Inicializa una nueva instancia de[`PngViewOptions`](../pngviewoptions) clase. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Inicializa una nueva instancia de[`PngViewOptions`](../pngviewoptions) clase. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Inicializa una nueva instancia de[`PngViewOptions`](../pngviewoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos comprimidos. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujo CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Fuente predeterminada que se usará cuando no se pueda encontrar una fuente particular utilizada en el documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de visualización de mensajes de correo electrónico. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Habilita la extracción de texto. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | La altura de una imagen de salida en píxeles. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opciones de visualización de archivos de datos de almacenamiento de correo. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Altura máxima de una imagen de salida en píxeles. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Ancho máximo de una imagen de salida en píxeles. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Las opciones de visualización de archivos de datos de MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Las opciones de visualización de documentos PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de presentación. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Las opciones de visualización de archivos de gestión de proyectos. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Habilita renderizar comentarios. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Habilita la visualización de páginas ocultas. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Habilita renderizar notas. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Las opciones de vista de archivos de hoja de cálculo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opciones de división de archivos de texto en páginas. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de archivos de Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La marca de agua de texto aplicada a cada página. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos web. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | El ancho de la imagen de salida en píxeles. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos de Word. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Aplica rotación en el sentido de las agujas del reloj a la página. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Las rotaciones de página. |

### Ver también

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* asamblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
