---
title: GetConsumptionCredit
second_title: GroupDocs.Viewer لمرجع .NET API
description: استرداد عدد الاعتمادات المستهلكة.
type: docs
weight: 30
url: /ar/net/groupdocs.viewer/metered/getconsumptioncredit/
---
## Metered.GetConsumptionCredit method

استرداد عدد الاعتمادات المستهلكة.

```csharp
public static decimal GetConsumptionCredit()
```

### أمثلة

المثال التالي يوضح كيفية استرداد عدد الاعتمادات المستهلكة.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);

decimal creditsConsumed = Metered.GetConsumptionCredit();
```

### أنظر أيضا

* class [Metered](../../metered)
* مساحة الاسم [GroupDocs.Viewer](../../metered)
* المجسم [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
