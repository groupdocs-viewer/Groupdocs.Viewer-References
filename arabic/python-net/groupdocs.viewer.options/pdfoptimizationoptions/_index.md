---
title: "الفئة PdfOptimizationOptions"
second_title: "مراجع API لـ GroupDocs.Viewer لـ Python عبر .NET"
description: "يمثل خيارات تحسين PDF لتطبيقها على ملف PDF الناتج."
type: docs
url: /ar/python-net/groupdocs.viewer.options/pdfoptimizationoptions/
is_root: false
weight: 150
---


## PdfOptimizationOptions class

يمثل خيارات تحسين PDF لتطبيقها على ملف PDF الناتج.

للتفاصيل وعينات الشيفرة، راجع صفحة الوثائق.

نوع PdfOptimizationOptions يعرض الأعضاء التالية:

### المنشئات
| المنشئ | الوصف |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/__init__/) | يُهيئ القيم الافتراضية للخيار MaxResolution إلى 300 والخيار ImageQuality إلى 100. |

### الخصائص
| خاصية | الوصف |
| :- | :- |
| [compress_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/compress_images/) | الخاصية تمكّن من ضغط الصور في ملف PDF الناتج. |
| [convert_to_gray_scale](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/convert_to_gray_scale/) | الخاصية تمكّن من تحويل ملف PDF الناتج إلى تدرجات الرمادي. |
| [image_quality](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/image_quality/) | جودة الصورة في ملف PDF الناتج، معبرًا عنها كنسبة مئوية. |
| [lineriaze](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/lineriaze/) | الخاصية تمكّن من تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب. |
| [max_resolution](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/max_resolution/) | أعلى دقة في ملف PDF الناتج. |
| [optimize_spreadsheets](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/optimize_spreadsheets/) | الخاصية التي تمكّن من تحسين جداول البيانات في ملفات PDF. |
| [remove_annotations](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_annotations/) | الخاصية تمكّن من إزالة التعليقات التوضيحية من ملف PDF الناتج. |
| [remove_form_fields](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_form_fields/) | الخاصية تمكّن من إزالة حقول النموذج من ملف PDF. |
| [remove_unused_objects](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_objects/) | الخاصية تزيل الكائنات غير المستخدمة (المهجورة) من ملف PDF. |
| [remove_unused_streams](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/remove_unused_streams/) | الخاصية تزيل التدفقات غير المستخدمة (المهجورة) من ملف PDF والتي يتم الإشارة إليها في قاموس موارد الصفحة ولكن لا تُستخدم أبداً في محتوى الصفحة. تكون معطلة بشكل افتراضي (`False`); ضبطها إلى `True` يقلل من حجم ملف PDF الناتج. |
| [resize_images](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/resize_images/) | الخاصية تمكّن من تعيين الحد الأقصى للدقة في ملف PDF الناتج. |
| [subset_fonts](/viewer/python-net/groupdocs.viewer.options/pdfoptimizationoptions/subset_fonts/) | الخاصية تقسم الخطوط إلى مجموعات فرعية في ملف PDF الناتج. |

### مثال

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import PdfViewOptions, PdfOptimizationOptions

def optimize_pdf():
    with Viewer("sample.docx") as viewer:
        view_options = PdfViewOptions("output/optimized.pdf")
        view_options.pdf_optimization_options = PdfOptimizationOptions()
        # تمكين التخطية لعرض ويب أسرع
        view_options.pdf_optimization_options.lineriaze = True
        # إزالة التعليقات التوضيحية وحقول النماذج لتقليل الحجم
        view_options.pdf_optimization_options.remove_annotations = True
        view_options.pdf_optimization_options.remove_form_fields = True

        viewer.view(view_options)
```

### انظر أيضًا
* module [`groupdocs.viewer.options`](/viewer/python-net/groupdocs.viewer.options/)
