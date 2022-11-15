---
title: GetConsumptionQuantity
second_title: GroupDocs.Viewer för .NET API-referens
description: Hämtar antalet bearbetade MB.
type: docs
weight: 40
url: /sv/net/groupdocs.viewer/metered/getconsumptionquantity/
---
## Metered.GetConsumptionQuantity method

Hämtar antalet bearbetade MB.

```csharp
public static decimal GetConsumptionQuantity()
```

### Exempel

Följande exempel visar hur man hämtar mängden bearbetade MB.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Se även

* class [Metered](../../metered)
* namnutrymme [GroupDocs.Viewer](../../metered)
* hopsättning [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->