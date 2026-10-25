---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Ruft die Anzahl der verbrauchten Credits ab."
type: docs
weight: 30
url: /de/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

Ruft die Anzahl der verbrauchten Credits ab.

```csharp
public static decimal GetConsumptionCredit()
```

### Beispiele

Das folgende Beispiel zeigt, wie die Anzahl der verbrauchten Credits abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
