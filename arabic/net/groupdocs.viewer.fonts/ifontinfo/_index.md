---
title: "IFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "واجهة عامة لجميع الخطوط التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة مثل PDF ومعالجة النصوص وجداول البيانات والعروض التقديمية."
type: docs
weight: 820
url: /ar/net/groupdocs.viewer.fonts/ifontinfo/
---

## IFontInfo interface

واجهة مشتركة لجميع الخطوط، التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة: PDF، WordProcessing، Spreadsheet، وPresentation.

```csharp
public interface IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/ifontinfo/content) { get; } | المحتوى الثنائي للخط كمصفوفة بايت، إذا كان متاحًا، أو `null` إذا لم يكن كذلك |
| [FamilyName](../../groupdocs.viewer.fonts/ifontinfo/familyname) { get; } | اسم العائلة للخط كسلسلة نصية |
| [Format](../../groupdocs.viewer.fonts/ifontinfo/format) { get; } | تنسيق هذا الخط كعدد تعداد — TrueType، TrueType Collection، OpenType، Embedded OpenType، أو Unknown. |
| [Style](../../groupdocs.viewer.fonts/ifontinfo/style) { get; } | نمط الخط كعدد تعداد — Regular، Bold، Italic، أو Bold Italic. قد تحتوي بعض صيغ المستندات على خطوط بنمط [`Regular`](../fontstyles/regular) فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/ifontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
