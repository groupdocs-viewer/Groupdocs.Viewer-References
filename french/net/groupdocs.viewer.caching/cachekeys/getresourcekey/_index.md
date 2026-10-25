---
title: "GetResourceKey"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Renvoie l'identifiant unique de l'entrée du cache qui représente l'objet Resourcegroupdocs.viewer.results/resource."
type: docs
weight: 70
url: /fr/net/groupdocs.viewer.caching/cachekeys/getresourcekey/
---

## CacheKeys.GetResourceKey method

Renvoie l'identifiant unique de l'entrée du cache qui représente l'objet [`Resource`](../../../groupdocs.viewer.results/resource).

```csharp
public static string GetResourceKey(int pageNumber, Resource resource)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de la page. |
| resource | Ressource | La ressource HTML. |

### Valeur de retour

Identifiant unique de l'entrée du cache qui représente l'objet [`Resource`](../../../groupdocs.viewer.results/resource).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *pageNumber* est inférieur ou égal à zéro. |
| ArgumentNullException | Lancé lorsque *resource* est nul. |

### Voir aussi

* class [Resource](../../../groupdocs.viewer.results/resource)
* class [CacheKeys](../../cachekeys)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
