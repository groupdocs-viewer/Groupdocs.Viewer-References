---
title: HtmlViewOptions
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Proporciona opciones para representar documentos en formato HTML.
type: docs
weight: 330
url: /es/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Proporciona opciones para representar documentos en formato HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos comprimidos. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujo CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Fuente predeterminada que se usará cuando no se pueda encontrar una fuente particular utilizada en el documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de visualización de mensajes de correo electrónico. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Cuando está habilitado, impide agregar fuentes al documento HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | La lista de nombres de fuentes, para excluir del documento HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Indica si optimizar el HTML de salida para imprimir. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | La altura de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Altura máxima de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Ancho máximo de una imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | El ancho de la imagen de salida en píxeles. (Al convertir una sola imagen a HTML solamente) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Opciones de visualización de archivos de datos de almacenamiento de correo. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Habilita la minificación de contenido HTML y recursos HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Las opciones de visualización de archivos de datos de MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Las opciones de visualización de documentos PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de presentación. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Las opciones de visualización de archivos de gestión de proyectos. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Habilita renderizar comentarios. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Habilita la visualización de páginas ocultas. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Habilita renderizar notas. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Habilita la representación receptiva; Las páginas web receptivas se muestran bien en dispositivos con diferentes tamaños de pantalla. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Habilita la representación de un documento completo en un archivo HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Las opciones de vista de archivos de hoja de cálculo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opciones de división de archivos de texto en páginas. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Las opciones de visualización de documentos de procesamiento de archivos de Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La marca de agua de texto aplicada a cada página. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Esta opción de representación le permite personalizar la apariencia de la salida HTML/PDF/PNG/JPEG al representar documentos de Word. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos incrustados. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos incrustados. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos incrustados. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos externos. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos externos. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Inicializa una nueva instancia de[`HtmlViewOptions`](../htmlviewoptions) clase para renderizar en HTML con recursos externos. |
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
