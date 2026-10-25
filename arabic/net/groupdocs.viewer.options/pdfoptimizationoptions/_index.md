---
title: "PdfOptimizationOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات تحسين PDF لتطبيقها على ملف PDF الناتج. للتفاصيل وعينات الكود راجع هذه الصفحةhttps//docs.groupdocs.com/viewer/net/optimizationpdfoptions/ وأقسامها الفرعية."
type: docs
weight: 400
url: /ar/net/groupdocs.viewer.options/pdfoptimizationoptions/
---

## PdfOptimizationOptions class

يحتوي على خيارات تحسين PDF لتطبيقها على ملف PDF الناتج. للحصول على تفاصيل وعينات الشيفرة، راجع هذه [الصفحة](https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) وأقسامها الفرعية.

```csharp
public class PdfOptimizationOptions
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | يضبط القيم الافتراضية لخيار MaxResolution إلى 300 وخيار ImageQuality إلى 100 |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [CompressImages](../../groupdocs.viewer.options/pdfoptimizationoptions/compressimages) { get; set; } | يفعل ضغط الصور في ملف PDF الناتج. |
| [ConvertToGrayScale](../../groupdocs.viewer.options/pdfoptimizationoptions/converttograyscale) { get; set; } | يفعل تحويل ملف PDF الناتج إلى تدرج الرمادي. |
| [ImageQuality](../../groupdocs.viewer.options/pdfoptimizationoptions/imagequality) { get; set; } | يضبط جودة الصورة في ملف PDF الناتج (بالنسبة المئوية). |
| [Lineriaze](../../groupdocs.viewer.options/pdfoptimizationoptions/lineriaze) { get; set; } | يفعل تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب. |
| [MaxResolution](../../groupdocs.viewer.options/pdfoptimizationoptions/maxresolution) { get; set; } | يضبط أقصى دقة في ملف PDF الناتج. |
| [OptimizeSpreadsheets](../../groupdocs.viewer.options/pdfoptimizationoptions/optimizespreadsheets) { get; set; } | يفعل تحسين جداول البيانات في ملفات PDF. |
| [RemoveAnnotations](../../groupdocs.viewer.options/pdfoptimizationoptions/removeannotations) { get; set; } | يفعل إزالة التعليقات من ملف PDF الناتج. |
| [RemoveFormFields](../../groupdocs.viewer.options/pdfoptimizationoptions/removeformfields) { get; set; } | يتيح إزالة حقول النموذج من ملف PDF. |
| [RemoveUnusedObjects](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedobjects) { get; set; } | يزيل الكائنات غير المستخدمة (المهجورة) من ملف PDF، والتي تم وضعها في مستند PDF ولكنها غير مُشار إليها من قواميس الموارد لأي صفحة وبالتالي لا تُستخدم على الإطلاق. تفعيل هذه الخاصية (`true`) سيقلل حجم مستند PDF الناتج. بشكل افتراضي تكون معطلة (`false`). |
| [RemoveUnusedStreams](../../groupdocs.viewer.options/pdfoptimizationoptions/removeunusedstreams) { get; set; } | يزيل التدفقات غير المستخدمة (المهجورة) من ملف PDF، والتي لا تزال مُشار إليها من قاموس موارد الصفحة، ولكنها في الواقع لا تُستخدم أبداً في محتويات الصفحة. بشكل افتراضي تكون معطلة (`false`)، وتفعيلها (`true`) سيقلل حجم مستند PDF الناتج. |
| [ResizeImages](../../groupdocs.viewer.options/pdfoptimizationoptions/resizeimages) { get; set; } | يتيح تعيين الحد الأقصى للدقة في ملف PDF الناتج. |
| [SubsetFonts](../../groupdocs.viewer.options/pdfoptimizationoptions/subsetfonts) { get; set; } | يقوم بإنشاء مجموعات فرعية للخطوط في ملف PDF الناتج. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
