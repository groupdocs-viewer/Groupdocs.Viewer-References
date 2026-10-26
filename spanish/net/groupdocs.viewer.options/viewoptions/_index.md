---
title: "ViewOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Contiene las opciones de renderizado."
type: docs
weight: 590
url: /es/net/groupdocs.viewer.options/viewoptions/
---

## ViewOptions class

Contiene las opciones de renderizado.

```csharp
public abstract class ViewOptions : BaseViewOptions
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Las opciones de vista de archivos de archivo. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Las opciones de vista de dibujos CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Establece la fuente predeterminada para un documento. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Las opciones de vista de mensajes de correo electrónico. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Las opciones de vista de archivos de datos de almacenamiento de correo. |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | La marca de agua de texto que se aplicará a cada página. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Las opciones de vista de archivos web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Las opciones de vista de archivos de procesamiento de texto. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Aplica la rotación en sentido horario a una página. |

## Campos

| Nombre | Descripción |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | La rotación de la página. |

### Ver también

* class [BaseViewOptions](../baseviewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
