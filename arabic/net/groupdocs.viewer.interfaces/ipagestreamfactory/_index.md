---
title: "IPageStreamFactory"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحدد الطرق المطلوبة لإنشاء وإطلاق دفق صفحة الإخراج."
type: docs
weight: 760
url: /ar/net/groupdocs.viewer.interfaces/ipagestreamfactory/
---

## IPageStreamFactory interface

يحدد الطرق المطلوبة لإنشاء وإطلاق دفق صفحة الإخراج.

```csharp
public interface IPageStreamFactory
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreatePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/createpagestream)(int) | ينشئ التدفق المستخدم لكتابة بيانات الصفحة الناتجة. |
| [ReleasePageStream](../../groupdocs.viewer.interfaces/ipagestreamfactory/releasepagestream)(int, Stream) | يطلق التدفق الذي أنشأته الطريقة [`CreatePageStream`](./createpagestream). |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Interfaces](../../groupdocs.viewer.interfaces)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
