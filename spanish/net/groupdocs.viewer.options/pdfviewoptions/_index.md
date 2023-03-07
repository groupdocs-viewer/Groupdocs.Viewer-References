---
title: PdfViewOptions
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Proporciona opciones para representar documentos en formato PDF.
type: docs
weight: 420
url: /es/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Proporciona opciones para representar documentos en formato PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Inicializa una nueva instancia de[`PdfViewOptions`](../pdfviewoptions) clase. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Inicializa una nueva instancia de[`PdfViewOptions`](../pdfviewoptions) clase. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Inicializa una nueva instancia de[`PdfViewOptions`](../pdfviewoptions) clase. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Inicializa una nueva instancia de[`PdfViewOptions`](../pdfviewoptions) clase. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Inicializa una nueva instancia de[`PdfViewOptions`](../pdfviewoptions) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos comprimidos. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujo CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Fuente predeterminada que se usará cuando no se pueda encontrar una fuente particular utilizada en el documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de visualización de mensajes de correo electrónico. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | La altura de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Altura máxima de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Ancho máximo de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | El ancho de la imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | La calidad de las imágenes JPG contenidas en el documento PDF de salida; Los valores válidos están entre 1 y 100; El valor predeterminado es 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opciones de visualización de archivos de datos de almacenamiento de correo. |
| [Optimize](../../groupdocs.viewer.options/pdfviewoptions/optimize) { get; set; } | Reduzca el tamaño del archivo de salida excluyendo fuentes comunes como Times New Roman y Arial, y aplicando otras técnicas de optimización. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Las opciones de visualización de archivos de datos de MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Las opciones de visualización de documentos PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de presentación. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Las opciones de visualización de archivos de gestión de proyectos. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Habilita renderizar comentarios. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Habilita la visualización de páginas ocultas. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Habilita renderizar notas. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Las opciones de seguridad del documento PDF de salida. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Las opciones de vista de archivos de hoja de cálculo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opciones de división de archivos de texto en páginas. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de archivos de Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La marca de agua de texto aplicada a cada página. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos web. |
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
* espacio de nombres [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* asamblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
