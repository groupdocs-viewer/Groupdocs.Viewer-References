---
title: "فئة WordProcessingSubstitutedFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على معلومات وصفية وبيانات ثنائية لخط واحد من مستند WordProcessing، والذي في الأصل لا يُستخدم في مستند نسخة Viewer المحملة، لكنه يعمل كخط بديل لتلك التي…"
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
is_root: false
weight: 120
---


## WordProcessingSubstitutedFontInfo class

يغلف معلومات التعريف والبيانات الثنائية لخط واحد من مستند معالجة نصوص، والذي لا يُستخدم أصلاً في مستند مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) المحمَّل، لكنه يعمل كخط بديل للخطوط التي لا يمكن العثور عليها على الجهاز الهدف. الخطوط البديلة موجودة فقط لعائلة صيغ معالجة النصوص.

هيكل غير قابل للتغيير. يتم إنشاء مثيلاته وإرجاعها عبر واجهة برمجة التطبيقات العامة لـ [`GroupDocs.Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) وعادةً لا ينبغي للمستخدم إنشاءها. للحصول على تفاصيل، راجع الوثائق: https://docs.groupdocs.com/viewer/net/getting-used-fonts/

نوع WordProcessingSubstitutedFontInfo يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/serialize_to_css_text_writer/) |  |
| [to_string](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/to_string/) | يرجع سلسلة تصحيح تحتوي على معلومات الخط بالتنسيق "original-name -> substituted-name style, format". |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/content/) | محتوى الخط المستبدل كمصفوفة بايت. لا يكون أبدًا None. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/family_name/) | اسم عائلة الخط المستبدل بدون نمط. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/format/) | تنسيق هذا الخط المستبدل (ليس الأصلي). |
| [original_family_name](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/original_family_name/) | اسم عائلة الخط الأصلي، الذي لا يمكن العثور عليه على الجهاز المستهدف، بدون نمط. لا يكون أبدًا فارغًا أو null. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/style/) | نمط الخط الأصلي — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
