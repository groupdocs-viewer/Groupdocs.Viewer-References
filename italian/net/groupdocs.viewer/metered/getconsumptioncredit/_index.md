---
title: GetConsumptionCredit
second_title: Riferimento API GroupDocs.Viewer per .NET
description: Recupera il conteggio dei crediti consumati.
type: docs
weight: 30
url: /it/net/groupdocs.viewer/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

Recupera il conteggio dei crediti consumati.

```csharp
public static decimal GetConsumptionCredit()
```

### Esempi

L'esempio seguente mostra come recuperare il conteggio dei crediti consumati.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Guarda anche

* class [Metered](../../metered)
* spazio dei nomi [GroupDocs.Viewer](../../metered)
* assemblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->