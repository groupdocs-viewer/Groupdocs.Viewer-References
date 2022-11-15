---
title: WordProcessingOptions
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Ces options de rendu vous permettent de personnaliser lapparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Word.
type: docs
weight: 620
url: /fr/net/groupdocs.viewer.options/wordprocessingoptions/
---
## WordProcessingOptions class

Ces options de rendu vous permettent de personnaliser l'apparence de la sortie HTML/PDF/PNG/JPEG lors du rendu de documents Word.

```csharp
public class WordProcessingOptions
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Fournit des options pour le rendu des documents de traitement de texte. |

## Propriétés

| Nom | La description |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | La distance (en points) entre le bord inférieur de la page et la limite inférieure du corps du texte. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens, latins ou cyrilliques. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | La distance (en points) entre le bord gauche de la page et la limite gauche du corps du texte. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | La taille de la page de sortie. La valeur par défaut estUnspecified ce qui signifie qu'une taille de page est définie dans les paramètres d'une page (Configuration de la page) est utilisé.  Lors du rendu des fichiers HTM et HTML, la taille de page par défaut est définie sur Lettre 792 x 612 points. Par conséquent, une partie du contenu peut ne pas tenir dans le cadre de la page. Définissez une taille de page plus grande, par exempleA3 pour s'adapter au contenu. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Active le rendu des modifications suivies (révisions). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | La distance (en points) entre le bord droit de la page et la limite droite du corps du texte. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | La distance (en points) entre le bord supérieur de la page et la limite supérieure du corps du texte. |

### Remarques

Voir aussi  Rendre des documents Word sous forme de fichiers HTML, PDF ou image pour plus de détails et des extraits de code.

### Voir également

* espace de noms [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* Assemblée [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->