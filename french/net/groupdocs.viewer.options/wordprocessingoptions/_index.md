---
title: "WordProcessingOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Contient des options pour le rendu des documents Word. Pour plus de détails, voir la documentationhttps//docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /fr/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

Contient des options pour le rendu des documents Word. Pour plus de détails, consultez la [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | Contient des options pour le rendu des documents de traitement de texte. Pour plus de détails, voir la [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## Propriétés

| Nom | Description |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | Définit la marge inférieure d'une page. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | Cette option active le crénage et d'autres fonctionnalités OpenType lors du rendu des scripts arabes, hébreux, indiens basés sur le latin ou cyrilliques. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | Obtient ou définit la résolution horizontale des images générées en points par pouce. Cette option est utilisée uniquement lors du rendu des documents WordProcessing au format PNG ou JPEG. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | Définit la marge gauche d'une page. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | Permet d'appliquer de force la numérotation des pages pour le document WordProcessing chargé. Par défaut, c'est NotApply — le document reste intact. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | La taille de la page de sortie. La valeur par défaut est Unspecified, ce qui signifie qu'une taille de page définie dans les paramètres de page (Mise en page) est utilisée. Lors du rendu des fichiers HTM et HTML, la taille de page par défaut est définie sur Letter 792 x 612 points. En conséquence, une partie du contenu peut ne pas tenir dans le cadre de la page. Définissez une taille de page plus grande, par ex. A3, pour faire tenir le contenu. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | Active le rendu des modifications suivies (révisions). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | Définit la marge droite d'une page. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | Définit la marge supérieure d'une page. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | Lors du rendu vers HTML ou PDF, vous pouvez définir cette option sur `true` pour désactiver la navigation depuis la table des matières. Pour le rendu HTML, les balises `a` avec des liens relatifs seront remplacées par des balises `span`, supprimant la fonctionnalité tout en conservant l'apparence visuelle. Pour le rendu PDF, la table des matières sera rendue en texte brut sans liens vers les sections du document. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | Obtient ou définit une valeur déterminant si les champs de certains types doivent être mis à jour avant d'enregistrer le document WordProcessing d'entrée aux formats de sortie HTML, PDF, PNG ou JPEG. La valeur par défaut pour cette propriété est `true` — les champs seront mis à jour avant l'enregistrement. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | Obtient ou définit la résolution verticale des images générées en points par pouce. Cette option est utilisée uniquement lors du rendu des documents WordProcessing au format PNG ou JPEG. |

## Méthodes

| Nom | Description |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | Crée et renvoie une copie profonde complète de ces options |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | Détermine si l'instance spécifiée de [`WordProcessingOptions`](../wordprocessingoptions) est égale à celle-ci |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
