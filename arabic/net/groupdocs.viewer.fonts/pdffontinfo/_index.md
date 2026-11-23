---
title: "PdfFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على معلومات التعريف والبيانات الثنائية لخط واحد من مستند PDF تم تحميله في كائن Viewer../groupdocs.viewer/viewer. يُستخدم هذا الخط في محتوى المستند ويتم تضمينه داخل المستند نفسه أو يتم تثبيته في نظام التشغيل حيث يعمل GroupDocs.Viewer."
type: docs
weight: 840
url: /ar/net/groupdocs.viewer.fonts/pdffontinfo/
---

## PdfFontInfo structure

يحتوي على معلومات التعريف والبيانات الثنائية لخط واحد من مستند PDF، تم تحميله في كائن [`Viewer`](../../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ويتم تضمينه داخل المستند نفسه أو يتم تثبيته في نظام التشغيل حيث يعمل GroupDocs.Viewer.

```csharp
public struct PdfFontInfo : IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Content](../../groupdocs.viewer.fonts/pdffontinfo/content) { get; } | محتوى هذا الخط كمصفوفة بايت. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/pdffontinfo/familyname) { get; } | اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو سلسلةً فارغة |
| [Format](../../groupdocs.viewer.fonts/pdffontinfo/format) { get; } | تنسيق هذا الخط. قد تستخدم المستندات الخطوط بالتنسيقات التالية: TrueType، TrueType Collection، OpenType، Embedded OpenType. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد قيمة Unknown. |
| [IsEmbedded](../../groupdocs.viewer.fonts/pdffontinfo/isembedded) { get; } | يشير إلى ما إذا كان هذا الخط مضمّنًا داخل مستند PDF، محمَّلًا في مثيل [`Viewer`](../../groupdocs.viewer/viewer) (`true`)، أم لا. |
| [IsInstalled](../../groupdocs.viewer.fonts/pdffontinfo/isinstalled) { get; } | يشير إلى ما إذا كان هذا الخط موجودًا (مثبتًا) في نظام التشغيل حيث يعمل GroupDocs.Viewer |
| [Style](../../groupdocs.viewer.fonts/pdffontinfo/style) { get; } | نمط الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/pdffontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |

### انظر أيضًا

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
