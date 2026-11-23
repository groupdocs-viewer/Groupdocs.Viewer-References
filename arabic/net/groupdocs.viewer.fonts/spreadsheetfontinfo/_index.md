---
title: "SpreadsheetFontInfo"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Spreadsheet تم تحميله في Viewer../groupdocs.viewer/viewer. لا يمكن لمستندات Spreadsheet أن تحتوي خطوطًا مضمّنة لذا فإن هذا الخط المحدد إذا تم إرجاعه بواسطة طريقة GetAllFonts../groupdocs.viewer/viewer/getallfonts يكون مُثبتًا في نظام التشغيل حيث يعمل GroupDocs.Viewer."
type: docs
weight: 870
url: /ar/net/groupdocs.viewer.fonts/spreadsheetfontinfo/
---

## SpreadsheetFontInfo structure

يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Spreadsheet، تم تحميله في مثيل [`Viewer`](../../groupdocs.viewer/viewer). لا يمكن لمستندات Spreadsheet أن تحتوي خطوطًا مضمّنة، لذا فإن هذا الخط المحدد، إذا تم إرجاعه بواسطة طريقة [`GetAllFonts`](../../groupdocs.viewer/viewer/getallfonts)، يكون مُثبتًا في نظام التشغيل، حيث يعمل GroupDocs.Viewer.

```csharp
public struct SpreadsheetFontInfo : IFontInfo
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Charset](../../groupdocs.viewer.fonts/spreadsheetfontinfo/charset) { get; } | مجموعة الأحرف لهذا الخط |
| [Color](../../groupdocs.viewer.fonts/spreadsheetfontinfo/color) { get; } | لون هذا الخط |
| [Content](../../groupdocs.viewer.fonts/spreadsheetfontinfo/content) { get; } | محتوى هذا الخط كمصفوفة بايت. إذا كان هناك فقط معلومات تعريف عن هذا الخط، لكن محتواه الثنائي غير متاح، فإن هذه الخاصية تُعيد `null`. |
| [FamilyName](../../groupdocs.viewer.fonts/spreadsheetfontinfo/familyname) { get; } | اسم عائلة الخط، بدون نمط، لا يكون أبداً فارغًا أو سلسلةً فارغة |
| [Format](../../groupdocs.viewer.fonts/spreadsheetfontinfo/format) { get; } | تنسيق هذا الخط |
| [IsStrikeout](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isstrikeout) { get; } | يشير إلى ما إذا كان الخط يحتوي على خط عبر واحد |
| [IsUnderline](../../groupdocs.viewer.fonts/spreadsheetfontinfo/isunderline) { get; } | يشير إلى ما إذا كان الخط يحتوي على خط تحت |
| [Style](../../groupdocs.viewer.fonts/spreadsheetfontinfo/style) { get; } | نمط هذا الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SerializeToCss](../../groupdocs.viewer.fonts/spreadsheetfontinfo/serializetocss)(TextWriter) | يسلسل معلومات هذا الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد |

### انظر أيضًا

* interface [IFontInfo](../ifontinfo)
* namespace [GroupDocs.Viewer.Fonts](../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
