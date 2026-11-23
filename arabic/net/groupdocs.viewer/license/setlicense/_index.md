---
title: "SetLicense"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يرخص المكوّن."
type: docs
weight: 20
url: /ar/net/groupdocs.viewer/license/setlicense/
---

## SetLicense(Stream) {#setlicense}

يرخص المكوّن.

```csharp
public void SetLicense(Stream licenseStream)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| licenseStream | تدفق | دفق الترخيص. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | يُطرح عندما يكون *licenseStream* null. |

### أمثلة

المثال التالي يوضح كيفية تعيين ترخيص بتمرير Stream لملف الترخيص.

```csharp
using (FileStream licenseStream = File.OpenRead("GroupDocs.Viewer.lic"))
{
    License license = new License();
    license.SetLicense(licenseStream);
}
```

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## SetLicense(string) {#setlicense_1}

يرخص المكوّن.

```csharp
public void SetLicense(string licensePath)
```

| Parameter | النوع | الوصف |
| --- | --- | --- |
| licensePath | String | مسار ملف الترخيص. |

### الاستثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | يُطرح عندما يكون *licensePath* null أو سلسلة فارغة. |

### أمثلة

المثال التالي يوضح كيفية تعيين ترخيص بتمرير مسار إلى ملف الترخيص.

```csharp
string licensePath = "GroupDocs.Viewer.lic";
License license = new License();
license.SetLicense(licensePath);
```

### انظر أيضًا

* class [License](../../license)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
