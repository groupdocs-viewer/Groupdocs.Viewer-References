---
title: "HtmlViewOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene opciones para renderizar documentos en formato HTML. Para más detalles, consulte el topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ y sus hijos."
type: docs
weight: 320
url: /es/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Contiene opciones para renderizar documentos en formato HTML. Para más detalles, consulte el [tema](https://docs.groupdocs.com/viewer/net/rendering-to-html/) y sus subtemas.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos de archivo. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujos CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Establece la fuente predeterminada para un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de vista de mensajes de correo electrónico. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Desactiva la incorporación de cualquier fuente en el documento HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | La lista de nombres de fuentes a excluir del documento HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Habilita la optimización del HTML de salida para impresión. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | La altura de una imagen de salida (en píxeles). La propiedad está disponible solo al convertir una sola imagen a HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Altura máxima de una imagen de salida (en píxeles). La propiedad está disponible solo al convertir una sola imagen a HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Anchura máxima de una imagen de salida (en píxeles). La propiedad está disponible solo al convertir una sola imagen a HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | La anchura de la imagen de salida (en píxeles). La propiedad está disponible solo al convertir una sola imagen a HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Las opciones de vista de archivos de datos de almacenamiento de correo. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Habilita la minificación del contenido HTML y los recursos HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Las opciones de vista de archivos de datos de Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Las opciones de vista de documentos PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Las opciones de vista de archivos de presentación. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Las opciones de vista de archivos de gestión de proyectos. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Desactiva la representación de comentarios cuando se establece en `true`. Por defecto es `false` — se muestran todos los comentarios. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Permite eliminar el código fuente JavaScript de los enlaces en los documentos HTML resultantes, al renderizar documentos de entrada que contienen scripts. Por defecto está habilitado (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Habilita la representación de páginas ocultas. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Habilita la representación de notas y anotaciones para algunos formatos. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Habilita la renderización responsiva. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Habilita la renderización de un documento completo en un solo archivo HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Las opciones de vista de archivos de hoja de cálculo. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Opciones de vista de archivos de texto. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Las opciones de vista de archivos Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La marca de agua de texto que se aplicará a cada página. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Las opciones de vista de archivos web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Las opciones de vista de archivos de procesamiento de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos incrustados. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos incrustados. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos incrustados. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos externos. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos externos. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Inicializa una instancia de la clase [`HtmlViewOptions`](../htmlviewoptions) para renderizar en HTML con recursos externos. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Aplica la rotación en sentido horario a una página. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | La rotación de la página. |

### Ver también

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
