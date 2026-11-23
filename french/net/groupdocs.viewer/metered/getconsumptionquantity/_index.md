---
title: "GetConsumptionQuantity"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Récupère la quantité de Mo traités."
type: docs
weight: 40
url: /fr/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

Récupère la quantité de Mo traités.

```csharp
public static decimal GetConsumptionQuantity()
```

### Exemples

L'exemple suivant montre comment récupérer la quantité de Mo traités.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Voir aussi

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
