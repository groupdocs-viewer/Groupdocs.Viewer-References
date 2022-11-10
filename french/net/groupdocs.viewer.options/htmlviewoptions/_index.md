---
title: HtmlViewOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Fournit des options pour rendre les documents au format HTML.
type: docs
weight: 330
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

Fournit des options pour rendre les documents au format HTML.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Propriétés

| Nom | La description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archives. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage du dessin CAO. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Lorsqu'il est activé, il empêche l'ajout de polices dans le document HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | La liste des noms de polices à exclure du document HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Indique s'il faut optimiser la sortie HTML pour l'impression. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | La hauteur d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Hauteur maximale d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Largeur maximale d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | La largeur de l'image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Options d'affichage des fichiers de données de stockage de courrier. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Active la minification du contenu HTML et des ressources HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage des documents PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des documents de traitement de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Active le rendu des commentaires. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active les notes de rendu. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Active le rendu réactif ; Les pages Web réactives s'affichent bien sur des appareils avec une taille d'écran différente. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Active le contenu HTML sera rendu sur une seule page |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Fichiers texte fractionnés en options de pages. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des documents de traitement des fichiers Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane de texte appliqué à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Word. |

## Méthodes

| Nom | La description |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources intégrées. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources intégrées. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources intégrées. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialise la nouvelle instance de[`HtmlViewOptions`](../htmlviewoptions) classe pour le rendu en HTML avec des ressources externes. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applique une rotation dans le sens des aiguilles d'une montre à la page. |

## Des champs

| Nom | La description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Les rotations de pages. |

### Voir également

* class [ViewOptions](../viewoptions)
* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
