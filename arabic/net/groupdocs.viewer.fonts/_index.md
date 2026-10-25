---
title: "GroupDocs.Viewer.Fonts"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "توفر مساحة الاسم فئات وتعدادات لإدارة الخطوط المستخدمة أثناء عملية التصيير."
type: docs
weight: 50
url: /ar/net/groupdocs.viewer.fonts/
---

توفر مساحة الاسم فئات وتعدادات لإدارة الخطوط المستخدمة أثناء عملية التصيير.

## الفئات

| الفئة | الوصف |
| --- | --- |
| [FolderFontSource](./folderfontsource) | يمثل المجلد الذي يحتوي على خطوط TrueType. |
| [FontSettings](./fontsettings) | يوفر طرقًا للعمل مع المصادر للبحث عن خطوط TrueType. |
## Structures

| الهيكل | الوصف |
| --- | --- |
| [FontStyles](./fontstyles) | يمثل 4 أنماط محتملة للخط، المستخدمة في المستند: Regular، Bold، Italic، أو Bold Italic |
| [PdfFontInfo](./pdffontinfo) | يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند PDF، تم تحميله في مثيل [`Viewer`](../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [PresentationFontInfo](./presentationfontinfo) | يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Presentation، تم تحميله في مثيل [`Viewer`](../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [SpreadsheetFontInfo](./spreadsheetfontinfo) | يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند Spreadsheet، تم تحميله في مثيل [`Viewer`](../groupdocs.viewer/viewer). لا يمكن لمستندات Spreadsheet أن تحتوي على خطوط مدمجة، لذا فإن هذا الخط المحدد، إذا تم إرجاعه بواسطة طريقة [`GetAllFonts`](../groupdocs.viewer/viewer/getallfonts)، يكون مُثبتًا في نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [WordProcessingFontInfo](./wordprocessingfontinfo) | يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند WordProcessing، تم تحميله في مثيل [`Viewer`](../groupdocs.viewer/viewer). يُستخدم هذا الخط في محتوى المستند ومضمن داخل المستند نفسه أو مُثبت في نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [WordProcessingSubstitutedFontInfo](./wordprocessingsubstitutedfontinfo) | يحتوي على بيانات التعريف والبيانات الثنائية لخط واحد من مستند WordProcessing، والذي في الأصل لا يُستخدم في المستند المحمَّل إلى مثيل [`Viewer`](../groupdocs.viewer/viewer)، لكنه يعمل كخط بديل لتلك التي لا يمكن العثور عليها على الجهاز الهدف. الخطوط البديلة موجودة فقط لعائلة صيغ WordProcessing. |
## الواجهات

| واجهة | الوصف |
| --- | --- |
| [IFontInfo](./ifontinfo) | واجهة مشتركة لجميع الخطوط، التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة: PDF، WordProcessing، Spreadsheet، وPresentation. |
| [IFontSource](./ifontsource) | واجهة علامة لمصادر الخطوط. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [FontFormat](./fontformat) | يمثل جميع صيغ الخطوط التي قد تكون موجودة في الموروثين من [`IFontInfo`](../groupdocs.viewer.fonts/ifontinfo). |
| [SearchOption](./searchoption) | يحدد ما إذا كان سيتم البحث في المجلد الحالي فقط، أو في المجلد الحالي وجميع المجلدات الفرعية. |

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
