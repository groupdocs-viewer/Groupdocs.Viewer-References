---
title: "فئة IFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل واجهة مشتركة لجميع الخطوط التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة: PDF، معالجة النصوص، جداول البيانات، والعروض التقديمية."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/ifontinfo/
is_root: false
weight: 50
---


## IFontInfo class

يمثل واجهة مشتركة لجميع الخطوط التي يمكن استخراجها من جميع عائلات صيغ المستندات المدعومة: PDF، معالجة النصوص، جداول البيانات، والعروض التقديمية.

يعرض نوع IFontInfo الأعضاء التالية:

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط هذه كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/serialize_to_css_text_writer/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/content/) | المحتوى الثنائي للخط كمصفوفة بايت، إذا كان متاحًا، أو None إذا لم يكن كذلك. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/family_name/) | اسم العائلة للخط كسلسلة نصية. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/format/) | تنسيق هذا الخط كعدد تعداد — TrueType، TrueType Collection، OpenType، Embedded OpenType، أو `FontFormat.unknown`. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/ifontinfo/style/) | نمط الخط كعدد تعداد (Regular، Bold، Italic، أو Bold Italic)؛ قد تدعم بعض صيغ المستندات فقط [`FontStyles.regular`](/viewer/python-net/groupdocs.viewer.fonts/fontstyles/regular/). |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
