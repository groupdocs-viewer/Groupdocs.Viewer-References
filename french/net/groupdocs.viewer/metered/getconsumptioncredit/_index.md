---
title: GetConsumptionCredit
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Récupère le nombre de crédits consommés.
type: docs
weight: 30
url: /fr/net/groupdocs.viewer/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Récupère le nombre de crédits consommés.

```csharp
public static decimal GetConsumptionCredit()
```

### Exemples

L'exemple suivant montre comment récupérer le nombre de crédits consommés.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Voir également

* class [Metered](../../metered)
* espace de noms [GroupDocs.Viewer](../../metered)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
