---
title: PdfViewOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Fournit des options pour rendre les documents au format PDF.
type: docs
weight: 420
url: /fr/net/groupdocs.viewer.options/pdfviewoptions/
---
## PdfViewOptions class

Fournit des options pour rendre les documents au format PDF.

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialise la nouvelle instance de[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialise la nouvelle instance de[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialise la nouvelle instance de[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialise la nouvelle instance de[`PdfViewOptions`](../pdfviewoptions) classe. |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialise la nouvelle instance de[`PdfViewOptions`](../pdfviewoptions) classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archives. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage du dessin CAO. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Police par défaut à utiliser lorsqu'une police particulière utilisée dans le document est introuvable. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | La hauteur d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Hauteur maximale d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Largeur maximale d'une image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | La largeur de l'image de sortie en pixels. (Lors de la conversion d'une seule image en HTML uniquement) |
| [JpgQuality](../../groupdocs.viewer.options/pdfviewoptions/jpgquality) { get; set; } | La qualité des images JPG contenues dans le document PDF de sortie ; Les valeurs valides sont comprises entre 1 et 100 ; La valeur par défaut est 90. |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Options d'affichage des fichiers de données de stockage de courrier. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données MS Outlook. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage des documents PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des documents de traitement de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | Active le rendu des commentaires. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active les notes de rendu. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Les options de sécurité des documents PDF de sortie. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Fichiers texte fractionnés en options de pages. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des documents de traitement des fichiers Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane de texte appliqué à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Web. |
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
* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
