---
title: "SpreadsheetOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour le rendu des feuilles de calcul. Pour plus de détails, voir les éléments enfants de la rubrique Render spreadsheet fileshttps//docs.groupdocs.com/viewer/net/renderspreadsheets/ topic."
type: docs
weight: 530
url: /fr/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

Contient des options pour le rendu des feuilles de calcul. Pour plus de détails, consultez les sous‑sections du sujet [Render spreadsheet files](https://docs.groupdocs.com/viewer/net/render-spreadsheets/).

```csharp
public class SpreadsheetOptions
```

## Propriétés

| Nom | Description |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | Définit la marge inférieure d'une page lors de la conversion en PDF. |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | Le nombre de colonnes à inclure sur chaque page lors du fractionnement de la feuille de calcul en pages. |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | Le nombre de lignes à inclure sur chaque page lors du fractionnement de la feuille de calcul en pages. |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | Détecte un séparateur (pour les fichiers CSV/TSV). |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale des images générées en points par pouce. Cette option n'est utilisée que lors du rendu des feuilles de calcul au format PNG ou JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | Définit la marge gauche d'une page lors de la conversion en PDF. |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | Active le rendu des lignes de grille. |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | Active le rendu des en-têtes. |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | Active le rendu des colonnes masquées. |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | Active le rendu des lignes masquées. |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | Définit la marge droite d'une page lors de la conversion en PDF. |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | Désactive le rendu des colonnes vides. |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | Désactive le rendu des lignes vides. |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | Définit le mode de dépassement de texte pour le rendu des documents de feuille de calcul en HTML. Par défaut, c'est , ce qui imite le comportement par défaut de MS Excel. |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | Définit la marge supérieure d'une page lors de la conversion en PDF. |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale des images générées en points par pouce. Cette option est utilisée uniquement lors du rendu des feuilles de calcul en formats PNG ou JPEG. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour le rendu de la feuille entière sur une page. |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour diviser en pages selon les sauts de page. |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour le rendu uniquement des zones d'impression. |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour le rendu des zones d'impression et des sauts de page. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour le rendu de la feuille en pages. |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | Initialise une instance de la classe [`SpreadsheetOptions`](../spreadsheetoptions) pour le rendu de la feuille en pages. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
