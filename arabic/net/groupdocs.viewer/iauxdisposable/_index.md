---
title: "IAuxDisposable"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يوسع واجهة IDisposable القياسية ويسمح بالحصول على الحالة الحالية لكائن والاشتراك في حدث التخلص"
type: docs
weight: 20
url: /ar/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

يوسع واجهة IDisposable القياسية، ويسمح بالحصول على الحالة الحالية لكائن والاشتراك في حدث التخلص.

```csharp
public interface IAuxDisposable : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | يشير إلى ما إذا كان المورد قد تم التخلص منه بالفعل (`true`) أم لا (`false`) |

## الأحداث

| الاسم | الوصف |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | يحدث عندما يتم التخلص من الكائن، مباشرةً بعد إكمال عملية التخلص من الموارد بنجاح |

### انظر أيضًا

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
