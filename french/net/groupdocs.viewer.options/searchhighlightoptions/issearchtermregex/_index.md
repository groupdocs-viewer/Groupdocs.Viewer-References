---
title: "IsSearchTermRegEx"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Obtient ou définit une valeur indiquant si le terme de recherche doit être traité comme une expression régulière ou comme une chaîne littérale. La valeur par défaut est false, traité comme une chaîne littérale."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer.options/searchhighlightoptions/issearchtermregex/
---

## SearchHighlightOptions.IsSearchTermRegEx property

Obtient ou définit une valeur indiquant si le terme de recherche doit être traité comme une expression régulière ou comme un texte littéral. La valeur par défaut est `false` — traiter comme un texte littéral.

```csharp
public bool IsSearchTermRegEx { get; set; }
```

### Remarques

Si `true`, [`SearchTerm`](../searchterm) est interprété comme un motif Regex .NET.

Si `false`, [`SearchTerm`](../searchterm) est recherché comme une chaîne littérale dans le document.

### Voir aussi

* class [SearchHighlightOptions](../../searchhighlightoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
