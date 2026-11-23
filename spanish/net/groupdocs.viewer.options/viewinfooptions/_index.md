---
title: "ViewInfoOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para obtener información sobre la vista."
type: docs
weight: 580
url: /es/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Contiene opciones para obtener información sobre la vista.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos de archivo. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujos CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Establece la fuente predeterminada para un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de vista de mensajes de correo electrónico. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Habilita la extracción de texto. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | La altura de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Las opciones de vista de archivos de datos de almacenamiento de correo. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Establece la altura máxima de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Establece el ancho máximo de una imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Las opciones de vista de archivos de datos de Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Las opciones de vista de documentos PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Las opciones de vista de archivos de presentación. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Las opciones de vista de archivos de gestión de proyectos. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Desactiva la representación de comentarios cuando se establece en `true`. Por defecto es `false` — se muestran todos los comentarios. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Habilita la representación de páginas ocultas. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Habilita la representación de notas y anotaciones para algunos formatos. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Las opciones de vista de archivos de hoja de cálculo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opciones de vista de archivos de texto. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Las opciones de vista de archivos Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Las opciones de vista de archivos web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | El ancho de la imagen de salida (en píxeles, solo para renderizar a PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Las opciones de vista de archivos de procesamiento de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) para obtener información de la vista al renderizar en PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) basada en el objeto [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) basada en el objeto [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) basada en el objeto [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Inicializa una instancia de la clase [`ViewInfoOptions`](../viewinfooptions) basada en el objeto [`PngViewOptions`](../pngviewoptions). |

### Ver también

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
