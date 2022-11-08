---
title: PngViewOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Fournit des options pour rendre les documents au format PNG.
type: docs
weight: 440
url: /fr/net/groupdocs.viewer.options/pngviewoptions/
---
## PngViewOptions class

Fournit des options pour rendre les documents au format PNG.

```csharp
public class PngViewOptions : ViewOptions, IMaxSizeOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PngViewOptions](pngviewoptions#constructor)() | Initialise la nouvelle instance de[`PngViewOptions`](../pngviewoptions) classe. |
| [PngViewOptions](pngviewoptions#constructor_1)(CreatePageStream) | Initialise la nouvelle instance de[`PngViewOptions`](../pngviewoptions) classe. |
| [PngViewOptions](pngviewoptions#constructor_3)(IPageStreamFactory) | Initialise la nouvelle instance de[`PngViewOptions`](../pngviewoptions) classe. |
| [PngViewOptions](pngviewoptions#constructor_4)(string) | Initialise la nouvelle instance de[`PngViewOptions`](../pngviewoptions) classe. |
| [PngViewOptions](pngviewoptions#constructor_2)(CreatePageStream, ReleasePageStream) | Initialise la nouvelle instance de[`PngViewOptions`](../pngviewoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archives. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage du dessin CAO. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ExtractText](../../groupdocs.viewer.options/pngviewoptions/extracttext) { get; set; } | Active l'extraction de texte. |
| [Height](../../groupdocs.viewer.options/pngviewoptions/height) { get; set; } | La hauteur d'une image de sortie en pixels. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Options d'affichage des fichiers de données de stockage de courrier. |
| [MaxHeight](../../groupdocs.viewer.options/pngviewoptions/maxheight) { get; set; } | Hauteur maximale d'une image de sortie en pixels. |
| [MaxWidth](../../groupdocs.viewer.options/pngviewoptions/maxwidth) { get; set; } | Largeur maximale d'une image de sortie en pixels. |
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
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane de texte appliqué à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Web. |
| [Width](../../groupdocs.viewer.options/pngviewoptions/width) { get; set; } | La largeur de l'image de sortie en pixels. |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Word. |

## Méthodes

| Nom | La description |
| --- | --- |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | Applique une rotation dans le sens des aiguilles d'une montre à la page. |

## Des champs

| Nom | La description |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | Les rotations de pages. |

### Voir également

* class [ViewOptions](../viewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
