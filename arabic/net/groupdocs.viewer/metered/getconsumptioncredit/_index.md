---
title: "GetConsumptionCredit"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يسترجع عدد الأرصدة المستهلكة."
type: docs
weight: 30
url: /ar/net/groupdocs.viewer/metered/getconsumptioncredit/
---

## Metered.GetConsumptionCredit method

يسترجع عدد الأرصدة المستهلكة.

```csharp
public static decimal GetConsumptionCredit()
```

### أمثلة

المثال التالي يوضح كيفية استرجاع عدد الأرصدة المستهلكة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
