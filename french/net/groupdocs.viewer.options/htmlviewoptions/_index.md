---
title: "HtmlViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient les options pour le rendu des documents au format HTML. Pour plus de détails, consultez le topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ et ses enfants."
type: docs
weight: 320
url: /fr/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

Contient des options pour le rendu des documents au format HTML. Pour plus de détails, consultez le [topic](https://docs.groupdocs.com/viewer/net/rendering-to-html/) et ses sous‑sections.

```csharp
public class HtmlViewOptions : ViewOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archive. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage des dessins CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Définit la police par défaut pour un document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | Désactive l'ajout de toute police dans le document HTML. |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | La liste des noms de polices à exclure du document HTML. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | Active l'optimisation du HTML de sortie pour l'impression. |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | La hauteur d'une image de sortie (en pixels). La propriété n'est disponible que lors de la conversion d'une image unique en HTML. |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | Hauteur maximale d'une image de sortie (en pixels). La propriété est disponible uniquement lors de la conversion d'une image unique en HTML. |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | Largeur maximale d'une image de sortie (en pixels). La propriété est disponible uniquement lors de la conversion d'une image unique en HTML. |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | La largeur de l'image de sortie (en pixels). La propriété est disponible uniquement lors de la conversion d'une image unique en HTML. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Les options d'affichage des fichiers de données de stockage de courrier. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | Active la minification du contenu HTML et des ressources HTML. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données Microsoft Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage du document PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des fichiers de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Désactive le rendu des commentaires lorsqu'il est réglé sur `true`. Par défaut, il est `false` — tous les commentaires sont affichés. |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | Permet de supprimer le code source JavaScript des liens dans les documents HTML résultants, lors du rendu des documents d'entrée contenant des scripts. Par défaut, il est activé (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active le rendu des notes et des annotations pour certains formats. |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | Active le rendu adaptatif. |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | Active le rendu d'un document complet en un seul fichier HTML. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Options d'affichage des fichiers texte. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des fichiers Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane texte à appliquer à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Les options d'affichage des fichiers Web. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Les options d'affichage des fichiers de traitement de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources intégrées. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources externes. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources externes. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions). |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | Initialise une instance de la classe [`HtmlViewOptions`](../htmlviewoptions) pour le rendu en HTML avec des ressources externes. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applique la rotation horaire à une page. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | La rotation de la page. |

### Voir aussi

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
