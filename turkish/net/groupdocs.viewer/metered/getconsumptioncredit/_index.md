---
title: "GetConsumptionCredit"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Tüketilen kredi sayısını alır."
type: docs
weight: 30
url: /tr/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

Tüketilen kredi sayısını alır.

```csharp
public static decimal GetConsumptionCredit()
```

### Örnekler

Aşağıdaki örnek, tüketilen kredi sayısının nasıl alınacağını gösterir.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### Ayrıca Bakınız

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
