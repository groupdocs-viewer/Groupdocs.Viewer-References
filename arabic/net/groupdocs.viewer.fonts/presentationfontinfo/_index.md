---
title: "PresentationFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Presentation تم تحميله في Viewer../groupdocs.viewer/viewer. يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer."
type: docs
weight: 850
url: /ar/net/groupdocs.viewer.fonts/presentationfontinfo/
---

## PresentationFontInfo structure

يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Presentation، تم تحميله في مثيل [`Viewer`](../../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل، حيث يعمل GroupDocs.Viewer.

```csharp
public struct PresentationFontInfo : IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/presentationfontinfo/content) { get; } | محتوى هذا الخط كمصفوفة بايت. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/presentationfontinfo/familyname) { get; } | اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو سلسلةً فارغة |
| [Format](../../groupdocs.viewer.fonts/presentationfontinfo/format) { get; } | تنسيق هذا الخط. قد تستخدم المستندات الخطوط بالتنسيقات التالية: TrueType، TrueType Collection، OpenType، Embedded OpenType. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد قيمة Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/presentationfontinfo/isembedded) { get; } | يشير إلى ما إذا كان هذا الخط مضمّنًا داخل المستند، تم تحميله في مثيل [`Viewer`](../../groupdocs.viewer/viewer) (`true`)، أو أنه خط نظام (`false`). لا يمكن لمستندات Spreadsheet احتواء خطوط مضمّنة، لذا لهذه المستندات تُعيد هذه الخاصية دائمًا `false`. |
| [Style](../../groupdocs.viewer.fonts/presentationfontinfo/style) { get; } | نمط الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/presentationfontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |

### انظر أيضًا

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
