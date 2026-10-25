---
title: "الأذونات"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحدد أذونات مستند PDF."
type: docs
weight: 430
url: /ar/net/groupdocs.viewer.options/permissions/
---

## Permissions enumeration

يحدد أذونات مستند PDF.

```csharp
[Flags]
public enum Permissions
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| AllowAll | `0` | السماح بالطباعة، والتعديل، واستخراج البيانات. |
| DenyPrinting | `1` | منع الطباعة. |
| DenyModification | `2` | منع تعديل المحتوى، ملء النماذج، إضافة أو تعديل التعليقات التوضيحية. |
| DenyDataExtraction | `4` | منع استخراج النصوص والرسومات. |
| DenyAll | `7` | منع الطباعة، تعديل المحتوى واستخراج البيانات. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
