---
title: "WordProcessingSubstitutedFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُغلف البيانات الوصفية والبيانات الثنائية لخط واحد من مستند WordProcessing الذي في الأصل لا يُستخدم في المستند المحمَّل إلى Viewer../groupdocs.viewer/viewer، ولكنه يُستخدم كخط بديل للخطوط التي لا يمكن العثور عليها على الجهاز الهدف. الخطوط البديلة موجودة فقط لعائلة صيغ WordProcessing."
type: docs
weight: 890
url: /ar/net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---

## WordProcessingSubstitutedFontInfo structure

يُغلف البيانات الوصفية والبيانات الثنائية لخط واحد من مستند WordProcessing، والذي في الأصل لا يُستخدم في المستند المحمَّل إلى مثيل [`Viewer`](../../groupdocs.viewer/viewer)، ولكنه يُستخدم كخط بديل للخطوط التي لا يمكن العثور عليها على الجهاز الهدف. الخطوط البديلة موجودة فقط لعائلة صيغ WordProcessing.

```csharp
public struct WordProcessingSubstitutedFontInfo : IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content) { get; } | محتوى هذا الخط البديل كمصفوفة بايت. لا يكون أبداً `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/familyname) { get; } | اسم العائلة للخط **substituted**، بدون نمط، لا يكون أبداً null أو سلسلة فارغة |
| [Format](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format) { get; } | تنسيق هذا الخط البديل (ليس الأصلي). قد يكون TrueType أو TrueType Collection أو OpenType أو Embedded OpenType. بالنسبة للخط البديل، نظرًا لتوفر محتواه الثنائي بحكم التعريف، لا تُعيد هذه الخاصية أبداً قيمة Unknown. |
| [OriginalFamilyName](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/originalfamilyname) { get; } | اسم عائلة الخط الأصلي، الذي لا يمكن العثور عليه على الجهاز الهدف، بدون نمط، لا يكون أبداً null أو سلسلة فارغة |
| [Style](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style) { get; } | نمط الخط الأصلي — قد يكون Regular أو Bold أو Italic أو Bold Italic. عادةً ما يكون الخط البديل (لكن ليس دائمًا) بنفس النمط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/tostring)() | يعيد معلومات تصحيح حول بيانات هذا الخط وفق القالب التالي: "original-name -&gt; substituted-name style, format" |

### ملاحظات

هيكل غير قابل للتغيير. تُنتج مثيلاته وتُعاد بواسطة واجهة برمجة التطبيقات العامة لـ GroupDocs.Viewer وعادةً لا ينبغي إنشاؤها من قبل المستخدم. للحصول على تفاصيل، راجع [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### انظر أيضًا

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
