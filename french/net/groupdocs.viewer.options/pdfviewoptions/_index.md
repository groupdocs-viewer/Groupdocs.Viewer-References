---
title: "PdfViewOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient les options pour le rendu des documents au format PDF. Pour plus de détails, voir la documentationhttps//docs.groupdocs.com/viewer/net/renderingtopdf/."
type: docs
weight: 420
url: /fr/net/groupdocs.viewer.options/pdfviewoptions/
---

## PdfViewOptions class

Contient des options pour le rendu des documents au format PDF. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

```csharp
public class PdfViewOptions : ViewOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfViewOptions](pdfviewoptions#constructor)() | Initialise une instance de la classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_1)(CreateFileStream) | Initialise une instance de la classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_3)(IFileStreamFactory) | Initialise une instance de la classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_4)(string) | Initialise une instance de la classe [`PdfViewOptions`](../pdfviewoptions). |
| [PdfViewOptions](pdfviewoptions#constructor_2)(CreateFileStream, ReleaseFileStream) | Initialise une instance de la classe [`PdfViewOptions`](../pdfviewoptions). |

## Propriétés

| Nom | Description |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | Les options d'affichage des fichiers d'archive. |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | Les options d'affichage des dessins CAD. |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | Définit la police par défaut pour un document. |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | Les options d'affichage des messages électroniques. |
| [ImageHeight](../../groupdocs.viewer.options/pdfviewoptions/imageheight) { get; set; } | Définit la hauteur d'une image de sortie (en pixels). |
| [ImageMaxHeight](../../groupdocs.viewer.options/pdfviewoptions/imagemaxheight) { get; set; } | Définit la hauteur maximale d'une image de sortie (en pixels). |
| [ImageMaxWidth](../../groupdocs.viewer.options/pdfviewoptions/imagemaxwidth) { get; set; } | Définit la largeur maximale d'une image de sortie (en pixels). |
| [ImageWidth](../../groupdocs.viewer.options/pdfviewoptions/imagewidth) { get; set; } | Définit la largeur d'une image de sortie (en pixels). |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | Les options d'affichage des fichiers de données de stockage de courrier. |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Les options d'affichage des fichiers de données Microsoft Outlook. |
| [PdfOptimizationOptions](../../groupdocs.viewer.options/pdfviewoptions/pdfoptimizationoptions) { get; set; } | Réduit la taille du fichier PDF de sortie en appliquant des techniques d'optimisation avec différentes options. |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | Les options d'affichage du document PDF. |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | Les options d'affichage des fichiers de présentation. |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | Les options d'affichage des fichiers de gestion de projet. |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | Désactive le rendu des commentaires lorsqu'il est réglé sur `true`. Par défaut, il est `false` — tous les commentaires sont affichés. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | Active le rendu des pages cachées. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | Active le rendu des notes et des annotations pour certains formats. |
| [Security](../../groupdocs.viewer.options/pdfviewoptions/security) { get; set; } | Définit les options de sécurité du document PDF de sortie. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | Les options d'affichage des fichiers de feuille de calcul. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | Options d'affichage des fichiers texte. |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Les options d'affichage des fichiers Visio. |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | Le filigrane texte à appliquer à chaque page. |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Les options d'affichage des fichiers Web. |
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
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
