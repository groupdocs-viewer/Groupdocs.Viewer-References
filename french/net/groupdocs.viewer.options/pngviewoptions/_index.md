---
title: "PngViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient les options pour le rendu de documents au format PNG. Pour plus de détails, consultez cette page https//docs.groupdocs.com/viewer/net/renderingtopngorjpeg/ et ses sous‑pages."
type: docs
weight: 440
url: /fr/net/groupdocs.viewer.options/pngviewoptions/
---

## PngViewOptions class

Contient des options pour le rendu des documents au format PNG. Pour plus de détails, consultez cette [page](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/) et ses sous‑sections.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initialise une instance de la classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initialise une instance de la classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initialise une instance de la classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initialise une instance de la classe [`PngViewOptions`](../pngviewoptions). |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initialise une instance de la classe [`PngViewOptions`](../pngviewoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archive. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage des dessins CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Définit la police par défaut pour un document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Active l'extraction de texte. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | Définit la hauteur d'une image de sortie (en pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Les options d'affichage des fichiers de données de stockage de courrier. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Définit la hauteur maximale d'une image de sortie (en pixels). |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Définit la largeur maximale d'une image de sortie (en pixels). |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane texte à appliquer à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Les options d'affichage des fichiers Web. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | La largeur de l'image de sortie (en pixels). |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Les options d'affichage des fichiers de traitement de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applique la rotation horaire à une page. |

## Champs

| Nom | Description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | La rotation de la page. |

### Voir aussi

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
