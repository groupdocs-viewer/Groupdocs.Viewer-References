---
title: "فئة PdfFontInfo"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على بيانات التعريف والبيانات الثنائية لخط PDF تم تحميله في نسخة Viewer، وقد يكون مدمجًا في المستند أو مثبتًا على نظام التشغيل حيث يعمل GroupDocs.Viewer."
type: docs
url: /ar/python-net/groupdocs.viewer.fonts/pdffontinfo/
is_root: false
weight: 70
---


## PdfFontInfo class

يغلف البيانات الوصفية والبيانات الثنائية لخط PDF تم تحميله في مثيل [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/)، والذي قد يكون مدمجًا في المستند أو مثبتًا على نظام التشغيل حيث يعمل GroupDocs.Viewer.

نوع PdfFontInfo يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/__init__/) |  |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [serialize_to_css](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css/#output) | يقوم بتسلسل معلومات الخط هذه كقاعدة @font-face ويكتبها إلى كاتب النص المحدد. |
| [serialize_to_css_text_writer](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/serialize_to_css_text_writer/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [content](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/content/) | محتوى هذا الخط كمصفوفة بايت، أو None إذا كانت البيانات الوصفية فقط متاحة وكان المحتوى الثنائي غير متوفر. |
| [family_name](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/family_name/) | اسم عائلة الخط بدون نمط؛ لا يكون أبدًا None أو سلسلة فارغة. |
| [format](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/format/) | تنسيق هذا الخط. |
| [is_embedded](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_embedded/) | تشير الخاصية إلى ما إذا كان الخط مدمجًا داخل مستند PDF وتم تحميله في نسخة Viewer (`True`)، أو لا. |
| [is_installed](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/is_installed/) | تشير الخاصية إلى ما إذا كان هذا الخط موجودًا (مثبتًا) في نظام التشغيل حيث يعمل GroupDocs.Viewer. |
| [style](/viewer/python-net/groupdocs.viewer.fonts/pdffontinfo/style/) | نمط الخط؛ قد يكون Regular أو Bold أو Italic أو Bold Italic. |

### انظر أيضًا
* module [`groupdocs.viewer.fonts`](/viewer/python-net/groupdocs.viewer.fonts/)
