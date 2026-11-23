---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Ruft die Menge der verarbeiteten MBs ab."
type: docs
weight: 40
url: /de/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

Ruft die Menge der verarbeiteten MBs ab.

```csharp
public static decimal GetConsumptionQuantity()
```

### Beispiele

Das folgende Beispiel zeigt, wie die Menge der verarbeiteten MB abgerufen wird.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Siehe auch

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
