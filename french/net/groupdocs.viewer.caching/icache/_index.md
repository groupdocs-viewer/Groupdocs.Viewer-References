---
title: "ICache"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Définit les méthodes requises pour stocker le document rendu et les ressources du document dans le cache."
type: docs
weight: 1000
url: /fr/net/groupdocs.viewer.caching/icache/
---

## ICache interface

Définit les méthodes requises pour stocker le document rendu et les ressources du document dans le cache.

```csharp
public interface ICache
```

## Méthodes

| Nom | Description |
| --- | --- |
| [GetKeys](../../groupdocs.viewer.caching/icache/getkeys)(string) | Renvoie toutes les clés correspondant au filtre. |
| [Set](../../groupdocs.viewer.caching/icache/set)(string, object) | Insère une entrée du cache dans le cache. |
| [TryGetValue&lt;TEntry&gt;](../../groupdocs.viewer.caching/icache/trygetvalue)(string, out TEntry) | Obtient l'entrée associée à cette clé si elle est présente. |

### Voir aussi

* namespace [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
