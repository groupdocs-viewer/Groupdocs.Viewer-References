---
title: "الفئة PdfOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل خيارات عرض إلى مستندات PDF."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptions/
is_root: false
weight: 160
---


## PdfOptions class

يمثل خيارات عرض إلى مستندات PDF.

للتفاصيل، راجع الوثائق.

نوع PdfOptions يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptions/__init__/) | ينشئ مثيلاً جديداً من الفئة PdfOptions. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [disable_chars_grouping](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_chars_grouping/) | الخاصية تُعطل تجميع الرموز لتحديد موضع الرموز بدقة أثناء عرض الصفحة. |
| [disable_copy_protection](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_copy_protection/) | الخاصية تُعطل حماية نسخ المحتوى عند العرض إلى HTML. |
| [disable_font_license_verifications](/viewer/python-net/groupdocs.viewer.options/pdfoptions/disable_font_license_verifications/) | الخاصية تُعطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
| [enable_font_hinting](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_font_hinting/) | الخاصية تُفعّل إرشاد الخط. |
| [enable_layered_rendering](/viewer/python-net/groupdocs.viewer.options/pdfoptions/enable_layered_rendering/) | الخاصية تُتيح عرض النص والرسومات بترتيب z الأصلي لمستند PDF عند العرض إلى HTML. |
| [fixed_layout](/viewer/python-net/groupdocs.viewer.options/pdfoptions/fixed_layout/) | خيار التخطيط الثابت يُتيح عرض مستندات PDF و EPUB إلى HTML بتخطيط ثابت. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptions/image_quality/) | جودة الصورة الناتجة لموارد الصور عند العرض إلى HTML. الجودة الافتراضية هي `ImageQuality.LOW`. |
| [render_original_page_size](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_original_page_size/) | تم ضبط حجم صفحة الإخراج ليتطابق مع حجم صفحة مستند PDF المصدر. |
| [render_text_as_image](/viewer/python-net/groupdocs.viewer.options/pdfoptions/render_text_as_image/) | الخيار يُتيح عرض النصوص في ملفات PDF كصورة في مخرجات HTML. |
| [wrap_images_in_svg](/viewer/python-net/groupdocs.viewer.options/pdfoptions/wrap_images_in_svg/) | الخاصية التي تُتيح تغليف كل صورة في مستند HTML الناتج داخل وسم SVG لتحسين جودة الإخراج. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PngViewOptions

with Viewer("sample.pdf") as viewer:
    view_options = PngViewOptions("output_{0}.png")
    # تفعيل إرشاد الخط عند عرض صفحات PDF كصور.
    view_options.pdf_options.enable_font_hinting = True
    viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
