---
title: "فئة SpreadsheetFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على البيانات الوصفية والبيانات الثنائية لخط من مستند جدول بيانات تم تحميله في مثيل Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/
is_root: false
weight: 100
---


## SpreadsheetFontInfo class

يغلف معلومات التعريف والبيانات الثنائية لخط من مستند جدول بيانات تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). لا يمكن لمستندات الجداول أن تحتوي على خطوط مدمجة، لذا يتم تثبيت الخط الذي تُعيده الدالة [`Viewer.get_all_fonts`](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) في نظام التشغيل حيث يعمل العارض.

يعرض نوع SpreadsheetFontInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/serialize_to_css_text_writer/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/charset/) | مجموعة الأحرف لهذا الخط. |
| [color](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/color/) | لون هذا الخط. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/content/) | محتوى هذا الخط كمصفوفة بايت. إذا كانت البيانات الوصفية فقط لهذا الخط متوفرة وكان المحتوى الثنائي غير متاح، فإن الخاصية تُعيد None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/family_name/) | اسم عائلة الخط، بدون النمط، لا يكون أبدًا null أو سلسلة فارغة. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/format/) | تنسيق هذا الخط. |
| [is_strikeout](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_strikeout/) | الخط يحتوي على شطب واحد. |
| [is_underline](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/is_underline/) | الخط يحتوي على تسطير. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/spreadsheetfontinfo/style/) | نمط هذا الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
