---
title: "SearchHighlightOptions"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Fournit des options pour la recherche et la mise en évidence du texte dans les documents chargés dans le Viewer../groupdocs.viewer/viewer class"
type: docs
weight: 500
url: /fr/net/groupdocs.viewer.options/searchhighlightoptions/
---

## SearchHighlightOptions class

Fournit des options pour la recherche et la mise en évidence du texte dans les documents, chargés dans la classe [`Viewer`](../../groupdocs.viewer/viewer)

```csharp
public sealed class SearchHighlightOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [SearchHighlightOptions](searchhighlightoptions)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/searchhighlightoptions/backgroundcolor) { get; set; } | Obtient ou définit la couleur d'arrière-plan pour la mise en évidence |
| [ForegroundColor](../../groupdocs.viewer.options/searchhighlightoptions/foregroundcolor) { get; set; } | Obtient ou définit la couleur de premier plan (texte) pour la mise en évidence |
| [IsSearchTermRegEx](../../groupdocs.viewer.options/searchhighlightoptions/issearchtermregex) { get; set; } | Obtient ou définit une valeur indiquant si le terme de recherche doit être traité comme une expression régulière ou comme un texte littéral. La valeur par défaut est `false` — traiter comme un texte littéral. |
| [SearchTerm](../../groupdocs.viewer.options/searchhighlightoptions/searchterm) { get; set; } | Obtient ou définit le texte (ou le motif d'expression régulière, si la propriété [`IsSearchTermRegEx`](./issearchtermregex) est `true`) à rechercher. |

### Voir aussi

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
