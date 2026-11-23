---
title: "SetMeteredKey"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يفعل المنتج باستخدام مفاتيح Metered."
type: docs
weight: 20
url: /ar/net/groupdocs.viewer/metered/setmeteredkey/
---

## Metered.SetMeteredKey method

يفعل المنتج باستخدام مفاتيح Metered.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| publicKey | String | المفتاح العام. |
| privateKey | String | المفتاح الخاص. |

### أمثلة

المثال التالي يوضح كيفية تنشيط المنتج باستخدام مفاتيح Metered.

```csharp
string publicKey = "Public Key";
string privateKey = "Private Key";

Metered metered = new Metered();
metered.SetMeteredKey(publicKey, privateKey);
```

### انظر أيضًا

* class [Metered](../../metered)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
