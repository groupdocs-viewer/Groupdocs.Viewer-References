---
title: "Search"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Effectue une recherche de texte et son surlignage s'il est trouvé dans le document chargé selon les options chargées"
type: docs
weight: 80
url: /fr/net/groupdocs.viewer/viewer/search/
---

## Viewer.Search method

Effectue une recherche de texte et son surlignage (si trouvé) dans le document chargé selon les options chargées.

```csharp
public void Search(SearchHighlightOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| options | SearchHighlightOptions | Options de recherche et de mise en évidence, cela inclut une phrase texte à rechercher. Ne peut pas être `null`. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Est levée lorsque l'argument *options* est `null` |

### Voir aussi

* class [SearchHighlightOptions](../../../groupdocs.viewer.options/searchhighlightoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
