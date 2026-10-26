---
title: "GetConsumptionQuantity"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "İşlenen MB miktarını alır."
type: docs
weight: 40
url: /tr/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

İşlenen MB miktarını alır.

```csharp
public static decimal GetConsumptionQuantity()
```

### Örnekler

Aşağıdaki örnek, işlenen MB miktarını nasıl alacağınızı gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
