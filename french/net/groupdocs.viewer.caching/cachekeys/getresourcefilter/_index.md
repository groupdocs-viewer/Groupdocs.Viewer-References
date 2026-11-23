---
title: "GetResourceFilter"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie la chaîne de filtre pour rechercher les entrées du cache qui représentent les objets Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 60
url: /fr/net/groupdocs.viewer.caching/cachekeys/getresourcefilter/
---

## CacheKeys.GetResourceFilter method

Renvoie la chaîne de filtre pour rechercher les entrées du cache qui représentent les objets [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceFilter(int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le nombre de pages. |

### Valeur de retour

Chaîne de filtre pour rechercher les entrées du cache qui représentent les objets [`Resource`](../../../groupdocs.viewer.results/resource).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *pageNumber* est inférieur ou égal à zéro. |

### Voir aussi

* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
