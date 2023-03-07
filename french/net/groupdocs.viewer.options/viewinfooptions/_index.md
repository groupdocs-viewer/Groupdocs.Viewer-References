---
title: ViewInfoOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Fournit des options utilisées pour récupérer des informations sur la vue.
type: docs
weight: 570
url: /fr/net/groupdocs.viewer.options/viewinfooptions/
---
## ViewInfoOptions class

Fournit des options utilisées pour récupérer des informations sur la vue.

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archives. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage du dessin CAO. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | Indique que l'extraction de texte est activée. |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | Hauteur de l'image (pour le rendu au format PNG/JPG uniquement) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Options d'affichage des fichiers de données de stockage de courrier. |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | Hauteur maximale de l'image de sortie (pour le rendu au format PNG/JPG uniquement) |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | Largeur maximale de l'image de sortie (pour le rendu au format PNG/JPG uniquement) |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage des documents PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des documents de traitement de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Active le rendu des commentaires. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active les notes de rendu. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Fichiers texte fractionnés en options de pages. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des documents de traitement des fichiers Visio. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Web. |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | Largeur de l'image (pour le rendu au format PNG/JPG uniquement) |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Word. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en HTML. |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en HTML. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en JPG. |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en JPG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en PNG. |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe pour récupérer des informations sur la vue lors du rendu en PNG. |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe basée sur[`HtmlViewOptions`](../htmlviewoptions) objet. |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe basée sur[`JpgViewOptions`](../jpgviewoptions) objet. |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | Initialise la nouvelle instance de[`ViewInfoOptions`](../viewinfooptions) classe basée sur[`PngViewOptions`](../pngviewoptions) objet. |

### Voir également

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
