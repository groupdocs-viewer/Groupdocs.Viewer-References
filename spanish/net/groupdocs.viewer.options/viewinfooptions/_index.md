---
title: ViewInfoOptions
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Proporciona opciones utilizadas para recuperar información sobre la vista.
type: docs
weight: 570
url: /es/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Proporciona opciones utilizadas para recuperar información sobre la vista.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos comprimidos. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujo CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Fuente predeterminada que se usará cuando no se pueda encontrar una fuente particular utilizada en el documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de visualización de mensajes de correo electrónico. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Indica que la extracción de texto está habilitada. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Altura de la imagen (solo para renderizar en PNG/JPG) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opciones de visualización de archivos de datos de almacenamiento de correo. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Altura máxima de la imagen de salida (solo para renderizar a PNG/JPG) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Ancho máximo de la imagen de salida (solo para renderizar a PNG/JPG) |
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
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Ancho de la imagen (solo para renderizar a PNG/JPG) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos de Word. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase para recuperar información sobre la vista al renderizar en PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase basada en[`HtmlViewOptions`](../htmlviewoptions) objeto. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase basada en[`JpgViewOptions`](../jpgviewoptions) objeto. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Inicializa una nueva instancia de[`ViewInfoOptions`](../viewinfooptions) clase basada en[`PngViewOptions`](../pngviewoptions) objeto. |

### Ver también

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* asamblea [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
