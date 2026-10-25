---
title: "OptionsOptimisationPdf"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient les options d'optimisation PDF à appliquer au fichier PDF de sortie. Pour plus de détails et des exemples de code, voir cette pagehttps//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ et ses sous‑pages."
type: docs
weight: 400
url: /fr/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

Contient les options d'optimisation PDF à appliquer au fichier PDF de sortie. Pour plus de détails et des exemples de code, consultez cette [page](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) et ses sous‑sections.

```csharp
public class PdfOptimizationOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | Configure les valeurs par défaut de l'option MaxResolution à 300 et de l'option ImageQuality à 100. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | Active la compression des images dans le fichier PDF de sortie. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | Active la conversion du fichier PDF de sortie en niveaux de gris. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | Définit la qualité de l'image dans le fichier PDF de sortie (en pourcentage). |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | Active l'optimisation du fichier PDF de sortie pour la visualisation en ligne avec un navigateur web. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | Définit la résolution maximale dans le fichier PDF de sortie. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | Active l'optimisation des feuilles de calcul dans les fichiers PDF. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | Active la suppression des annotations du fichier PDF de sortie. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | Permet de supprimer les champs de formulaire d'un fichier PDF. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | Supprime les objets inutilisés (orphelins) d'un fichier PDF, qui sont présents dans le document PDF mais ne sont référencés par aucun dictionnaire de ressources de page et ne sont donc pas du tout utilisés. Activer cette propriété (`true`) réduira la taille du document PDF généré. Par défaut, elle est désactivée (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | Supprime les flux inutilisés (orphelins) d'un fichier PDF, qui sont encore référencés dans le dictionnaire de ressources de la page mais ne sont jamais réellement utilisés dans le contenu de la page. Par défaut, elle est désactivée (`false`), son activation (`true`) réduira la taille du document PDF généré. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | Permet de définir la résolution maximale dans le fichier PDF de sortie. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | Sous-ensemble les polices dans le fichier PDF de sortie. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
