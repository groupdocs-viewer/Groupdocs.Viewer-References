---
title: "ViewInfoOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour récupérer des informations sur la vue."
type: docs
weight: 580
url: /fr/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

Contient des options pour récupérer des informations sur la vue.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archive. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage des dessins CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Définit la police par défaut pour un document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Active l'extraction de texte. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | La hauteur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Les options d'affichage des fichiers de données de stockage de courrier. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Définit la hauteur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Définit la largeur maximale d'une image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage du document PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des fichiers de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Désactive le rendu des commentaires lorsqu'il est réglé sur `true`. Par défaut, il est `false` — tous les commentaires sont affichés. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active le rendu des notes et des annotations pour certains formats. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Options d'affichage des fichiers texte. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des fichiers Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Les options d'affichage des fichiers Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | La largeur de l'image de sortie (en pixels, uniquement pour le rendu en PNG/JPG). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Les options d'affichage des fichiers de traitement de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en JPG. |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en PDF. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) pour récupérer des informations sur la vue lors du rendu en PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) basée sur l'objet [`HtmlViewOptions`](../htmlviewoptions). |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) basée sur l'objet [`JpgViewOptions`](../jpgviewoptions). |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) basée sur l'objet [`PdfViewOptions`](../pdfviewoptions). |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initialise une instance de la classe [`ViewInfoOptions`](../viewinfooptions) basée sur l'objet [`PngViewOptions`](../pngviewoptions). |

### Voir aussi

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
