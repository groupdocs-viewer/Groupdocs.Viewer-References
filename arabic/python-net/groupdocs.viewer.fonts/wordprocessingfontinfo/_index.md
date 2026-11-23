---
title: "الفئة WordProcessingFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على بيانات التعريف والبيانات الثنائية لخط من مستند WordProcessing تم تحميله في نسخة Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/
is_root: false
weight: 110
---


## WordProcessingFontInfo class

يغلف معلومات التعريف والبيانات الثنائية لخط من مستند معالجة نصوص تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/).

بنية غير قابلة للتغيير.

يتم إنشاء مثيلاته وإرجاعها عبر واجهة برمجة التطبيقات العامة لـ [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) وعادةً لا ينبغي للمستخدم إنشاءها.

للتفاصيل، راجع الوثائق: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

يعرض نوع WordProcessingFontInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/to_string/) | يعيد معلومات تصحيح حول بيانات هذا الخط وفق القالب التالي: "name style, embedded/system, format". |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [alt_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/alt_family_name/) | الاسم العائلي البديل للخط. إذا كان مفقودًا، يكون سلسلة فارغة. |
| [charset](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/charset/) | مجموعة الأحرف لهذا الخط. |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/content/) | محتوى هذا الخط كمصفوفة بايت. إذا كانت معلومات التعريف فقط متوفرة ولا يتوفر المحتوى الثنائي، فإن الخاصية تُعيد None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/family_name/) | اسم عائلة الخط بدون نمط؛ لا يكون أبدًا None أو سلسلة فارغة. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/format/) | تنسيق هذا الخط. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/is_embedded/) | تشير الخاصية إلى ما إذا كان هذا الخط مدمجًا داخل المستند، محملاً في نسخة [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`)، أو أنه خط نظام (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingfontinfo/style/) | نمط الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
