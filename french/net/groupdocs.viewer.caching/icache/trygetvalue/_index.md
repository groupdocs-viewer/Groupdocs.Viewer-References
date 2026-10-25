---
title: "TryGetValue"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Obtient l'entrée associée à cette clé si elle est présente."
type: docs
weight: 30
url: /fr/net/groupdocs.viewer.caching/icache/trygetvalue/
---

## ICache.TryGetValue&lt;TEntry&gt; method

Obtient l'entrée associée à cette clé si elle est présente.

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| Paramètre | Description |
| --- | --- |
| TEntry | Type d'entrée. |
| clé | Une clé identifiant l'entrée demandée. |
| value | La valeur trouvée ou null. |

### Valeur de retour

```csharp
True
```

si la clé a été trouvée.

### Voir aussi

* interface [ICache](../../icache)
* namespace [GroupDocs.Viewer.Caching](../../../groupdocs.viewer.caching)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
