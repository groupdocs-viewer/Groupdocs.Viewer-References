---
title: "الفئة PresentationFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل البيانات الوصفية والبيانات الثنائية لخط من مستند عرض تم تحميله في مثيل Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/presentationfontinfo/
is_root: false
weight: 80
---


## PresentationFontInfo class

يمثل معلومات التعريف والبيانات الثنائية لخط من مستند عرض تقديمي تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/). يُستخدم الخط في محتوى المستند وقد يكون مدمجًا في المستند أو مثبتًا على نظام التشغيل حيث يعمل العارض.

يعرض نوع PresentationFontInfo الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط هذه كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/serialize_to_css_text_writer/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/content/) | محتوى هذا الخط كمصفوفة بايت. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/family_name/) | اسم عائلة الخط بدون نمط؛ لا يكون أبدًا None أو سلسلة فارغة. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/format/) | تنسيق هذا الخط. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/is_embedded/) | تشير الخاصية إلى ما إذا كان الخط مضمّنًا داخل المستند وتم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) (`True`)، أو أنه خط نظام (`False`). |
| [style](/viewer/python-net/groupdocs.viewer.fonts/presentationfontinfo/style/) | نمط الخط — قد يكون Regular أو Bold أو Italic أو Bold Italic. |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
