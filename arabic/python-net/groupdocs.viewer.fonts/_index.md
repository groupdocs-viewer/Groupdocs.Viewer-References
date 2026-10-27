---
title: "groupdocs.viewer.fonts"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "إعداد تحميل الخطوط والاستبدال."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/
is_root: false
weight: 40
---


إعداد تحميل الخطوط والاستبدال.

### الفئات
| الفئة | الوصف |
| :- | :- |
| [`FolderFontSource`](/viewer/python-net/groupdocs.viewer.fonts/folderfontsource/) | يمثل المجلد الذي يحتوي على خطوط TrueType. |
| [`FontSettings`](/viewer/python-net/groupdocs.viewer.fonts/fontsettings/) | يوفر أساليب للعمل مع المصادر للبحث عن خطوط TrueType. |
| [`FontStyles`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/) | يمثل 4 أنماط محتملة للخط تُستخدم في المستند: عادي، عريض، مائل أو عريض مائل. |
| [`IFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/) | يمثل واجهة مشتركة لجميع الخطوط التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة: PDF، معالجة النصوص، جداول البيانات، والعروض التقديمية. |
| [`PdfFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/) | يغلف البيانات الوصفية والبيانات الثنائية لخط PDF تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)، والذي قد يكون مدمجًا في المستند أو مثبتًا على نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [`PresentationFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/) | يمثل معلومات التعريف والبيانات الثنائية لخط من مستند عرض تقديمي تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). يُستخدم الخط في محتوى المستند وقد يكون مدمجًا في المستند أو مثبتًا على نظام التشغيل حيث يعمل العارض. |
| [`SpreadsheetFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/) | يغلف معلومات التعريف والبيانات الثنائية لخط من مستند جدول بيانات تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). لا يمكن لمستندات الجداول أن تحتوي على خطوط مدمجة، لذا يتم تثبيت الخط الذي تُعيده الدالة [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) في نظام التشغيل حيث يعمل العارض. |
| [`WordProcessingFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/) | يغلف معلومات التعريف والبيانات الثنائية لخط من مستند معالجة نصوص تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). |
| [`WordProcessingSubstitutedFontInfo`](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/) | يغلف معلومات التعريف والبيانات الثنائية لخط واحد من مستند معالجة نصوص، والذي لا يُستخدم أصلاً في مستند مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) المحمَّل، لكنه يعمل كخط بديل للخطوط التي لا يمكن العثور عليها على الجهاز الهدف. الخطوط البديلة موجودة فقط لعائلة صيغ معالجة النصوص. |

### التعدادات
| تعداد | الوصف |
| :- | :- |
| [`FontFormat`](/viewer/python-net/groupdocs.viewer.fonts/fontformat/) |  |
| [`IFontSource`](/viewer/python-net/groupdocs.viewer.fonts/ifontsource/) | يمثل واجهة علامة لمصادر الخطوط. |
| [`SearchOption`](/viewer/python-net/groupdocs.viewer.fonts/searchoption/) |  |
