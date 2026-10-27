---
title: "الفئة WordProcessingOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يحتوي على خيارات لتصيير مستندات Word."
type: docs
url: /ar/python-net/groupdocs.viewer.options/wordprocessingoptions/
is_root: false
weight: 380
---


## WordProcessingOptions class

يحتوي على خيارات لتصيير مستندات Word.

للتفاصيل، راجع الوثائق على https://docs.groupdocs.com/viewer/net/render-word-documents/.

نوع WordProcessingOptions يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/__init__/) | يُهيئ الخيارات لتصيير مستندات معالجة الكلمات. |

### الطرق
| الطريقة | الوصف |
| :- | :- |
| [clone](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/clone/) | ينشئ ويُعيد نسخة عميقة كاملة من هذه الخيارات. |
| [equals](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals/#options) | يحدد ما إذا كانت المثيل المحدد [`WordProcessingOptions`](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/) مساوية لهذا المثيل. |
| [equals_word_processing_options](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/equals_word_processing_options/) |  |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [bottom_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/bottom_margin/) | الهامش السفلي للصفحة. |
| [enable_open_type_features](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/enable_open_type_features/) | الخيار يفعّل ضبط الحروف (kerning) وغيرها من ميزات OpenType عند تصيير النصوص العربية أو العبرية أو اللاتينية الهندية أو السيريالية. |
| [horizontal_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/horizontal_resolution/) | الدقة الأفقية للصور المُولَّدة بالنقطة لكل بوصة. يُستخدم هذا الخيار عند تصيير مستندات WordProcessing إلى صيغ PNG أو JPEG فقط. |
| [left_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/left_margin/) | الهامش الأيسر للصفحة. |
| [page_number_location](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_number_location/) | موقع ترقيم الصفحات للمستند WordProcessing المحمَّل، والذي يمكنه فرض ترقيم الصفحات؛ بشكل افتراضي يكون `WordsPageNumberLocation.not_apply`، مما يترك المستند كما هو. |
| [page_size](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/page_size/) | حجم الصفحة الناتجة. |
| [render_tracked_changes](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/render_tracked_changes/) | الخاصية تتيح تصيير التغييرات المتتبعة (المراجعات). |
| [right_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/right_margin/) | الهامش الأيمن للصفحة. |
| [top_margin](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/top_margin/) | الهامش العلوي للصفحة بالنقاط. |
| [unlink_table_of_contents](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/unlink_table_of_contents/) | الخيار يعطل التنقل من جدول المحتويات عندما يُضبط على True لتصيير HTML أو PDF. |
| [update_fields](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/update_fields/) | الخاصية تحدد ما إذا كانت الحقول من أنواع معينة تُحدَّث قبل حفظ مستند WordProcessing إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية هي True، مما يعني تحديث الحقول. |
| [vertical_resolution](/viewer/python-net/groupdocs.viewer.options/wordprocessingoptions/vertical_resolution/) | الدقة العمودية للصور المُولَّدة بالنقطة لكل بوصة، تُستخدم عند تصيير مستندات WordProcessing إلى صيغ PNG أو JPEG فقط. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions

with Viewer("with_tracked_changes.docx") as viewer:
    view_options = PdfViewOptions("output/word_with_tracked_changes.pdf")
    view_options.word_processing_options.render_tracked_changes = True
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
