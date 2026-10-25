---
title: "WordProcessingFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يُغلف البيانات الوصفية والبيانات الثنائية لخط واحد من مستند WordProcessing المحمَّل إلى مثيل Viewer../groupdocs.viewer/viewer. يُستخدم هذا الخط في محتوى المستند ومضمّن داخل المستند نفسه أو مثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer."
type: docs
weight: 880
url: /ar/net/groupdocs.viewer.fonts/wordprocessingfontinfo/
---

## WordProcessingFontInfo structure

يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند WordProcessing، تم تحميله في مثيل [`Viewer`](../../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer.

```csharp
public struct WordProcessingFontInfo : IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AltFamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/altfamilyname) { get; } | الاسم العائلي البديل للخط. إذا كان مفقودًا، يكون سلسلة فارغة. |
| [Charset](../../groupdocs.viewer.fonts/wordprocessingfontinfo/charset) { get; } | مجموعة الأحرف لهذا الخط |
| [Content](../../groupdocs.viewer.fonts/wordprocessingfontinfo/content) { get; } | محتوى هذا الخط كمصفوفة بايت. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/wordprocessingfontinfo/familyname) { get; } | اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو سلسلةً فارغة |
| [Format](../../groupdocs.viewer.fonts/wordprocessingfontinfo/format) { get; } | تنسيق هذا الخط. قد تستخدم المستندات الخطوط بالتنسيقات التالية: TrueType، TrueType Collection، OpenType، Embedded OpenType. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد قيمة Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/wordprocessingfontinfo/isembedded) { get; } | يشير إلى ما إذا كان هذا الخط مضمّنًا داخل المستند، تم تحميله في مثيل [`Viewer`](../../groupdocs.viewer/viewer) (`true`)، أو أنه خط نظام (`false`). |
| [Style](../../groupdocs.viewer.fonts/wordprocessingfontinfo/style) { get; } | نمط الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/wordprocessingfontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |
| override [ToString](../../groupdocs.viewer.fonts/wordprocessingfontinfo/tostring)() | يعيد معلومات تصحيح حول بيانات هذا الخط وفق القالب التالي: "name style, embedded/system, format" |

### ملاحظات

هيكل غير قابل للتغيير. تُنتج مثيلاته وتُعاد بواسطة واجهة برمجة التطبيقات العامة لـ GroupDocs.Viewer وعادةً لا ينبغي إنشاؤها من قبل المستخدم. للحصول على تفاصيل، راجع [documentation](https://docs.groupdocs.com/viewer/net/getting-used-fonts/).

### انظر أيضًا

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
