---
title: "GetConsumptionQuantity"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يسترجع مقدار الميجابايتات المعالجة."
type: docs
weight: 40
url: /ar/net/groupdocs.viewer/metered/getconsumptionquantity/
---

## Metered.GetConsumptionQuantity method

يسترجع مقدار الميجابايتات المعالجة.

```csharp
public static decimal GetConsumptionQuantity()
```

### أمثلة

المثال التالي يوضح كيفية استرجاع كمية الميجابايت المعالجة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal mbProcessed = Metered.GetConsumptionQuantity();
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
