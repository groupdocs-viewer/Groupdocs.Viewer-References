---
title: "فئة ViewOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "خيارات العرض."
type: docs
url: /ar/python-net/groupdocs.viewer.options/viewoptions/
is_root: false
weight: 340
---


## ViewOptions class

خيارات العرض.

نوع ViewOptions يعرض الأعضاء التالية:

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [rotate_page](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page/#page_number-rotation) | يطبق دورانًا باتجاه عقارب الساعة على الصفحة. |
| [rotate_page_int32](/viewer/python-net/groupdocs.viewer.options/viewoptions/rotate_page_int32/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [page_rotations](/viewer/python-net/groupdocs.viewer.options/viewoptions/page_rotations/) | دوران الصفحة. |
| [watermark](/viewer/python-net/groupdocs.viewer.options/viewoptions/watermark/) | علامة النص المائية التي تُطبق على كل صفحة. |
| [archive_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/archive_options/) | خيارات عرض ملفات الأرشيف. (موروثة من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [cad_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/cad_options/) | خيارات عرض رسومات CAD. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [default_font_name](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/default_font_name/) | الخط الافتراضي للمستند المستخدم أثناء العرض عندما يكون الخط المطلوب مفقودًا. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [email_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/email_options/) | خيارات عرض رسائل البريد الإلكتروني. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [mail_storage_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/mail_storage_options/) | خيارات عرض ملفات بيانات تخزين البريد. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [outlook_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/outlook_options/) | خيارات عرض ملفات بيانات Microsoft Outlook. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [pdf_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/pdf_options/) | خيارات عرض مستند PDF. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [presentation_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/presentation_options/) | خيارات عرض ملفات العروض التقديمية. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [project_management_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/project_management_options/) | خيارات عرض ملفات إدارة المشاريع. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [remove_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/remove_comments/) | الخاصية تعطل عرض التعليقات عندما تكون مضبوطة على True. بشكل افتراضي تكون False، لذا يتم عرض جميع التعليقات. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_comments](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_comments/) | الخاصية تمكّن أو تعطل عرض التعليقات. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_hidden_pages](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_hidden_pages/) | الخاصية تمكّن عرض الصفحات المخفية. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [render_notes](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/render_notes/) | الخاصية تمكّن عرض الملاحظات والتعليقات التوضيحية لبعض الصيغ. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [spreadsheet_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/spreadsheet_options/) | خيارات عرض ملفات الجداول. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [text_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/text_options/) | خيارات النص لعرض ملفات النص. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [visio_rendering_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/visio_rendering_options/) | خيارات عرض ملفات Visio. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [web_document_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/web_document_options/) | خيارات عرض ملفات الويب. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |
| [word_processing_options](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/word_processing_options/) | خيارات عرض ملفات معالجة النصوص. (موروث من [`BaseViewOptions`](/viewer/python-net/groupdocs.viewer.options/baseviewoptions/)) |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("sample.pptx") as viewer:
    view_options = PdfViewOptions("output.pdf")
    view_options.render_notes = True
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
