---
title: "CadOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لتصيير رسومات CAD. لمزيد من المعلومات وأمثلة الشيفرة راجع Render CAD drawings and models as HTML PDF and image fileshttps//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ وSpecify rendering options for CAD fileshttps//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/."
type: docs
weight: 280
url: /ar/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

يحتوي على خيارات لتصيير رسومات CAD. لمزيد من المعلومات وأمثلة الشيفرة، راجع [تصيير رسومات CAD والنماذج كملفات HTML وPDF وصور](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) و[تحديد خيارات التصيير لملفات CAD](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/).

```csharp
public class CadOptions
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | لون خلفية الصورة. |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | ضبط هذا العلم إلى `true` يفعّل وضع تحويل خاص يركز على الأداء لجميع الصيغ ضمن عائلة CAD — في هذا الوضع تكون سرعة التحويل أسرع بكثير، لكن جودة المستندات الناتجة تكون أسوأ بشكل ملحوظ. بشكل افتراضي يكون معطلاً (`false`) — جودة المستندات الناتجة هي الأفضل الممكنة على حساب الأداء. |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | ارتفاع النتيجة الناتجة (بالبكسل). |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | طبقات رسومات CAD التي سيتم تصييرها. |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | اسم التخطيط المحدد لتصيره. اسم التخطيط حساس لحالة الأحرف. |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - ملف تكوين plotter |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | علامة إذا كان يجب عرض التخطيطات من مستند CAD. |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | القيمة التي تزيد عن 1 تكبر نتيجة الإخراج؛ القيمة بين 0 و 1 تقلل نتيجة الإخراج. |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | مناطق الرسم التي سيتم عرضها. |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | عرض نتيجة الإخراج (بالبكسل). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | يُنشئ مثيلاً من الفئة [`CadOptions`](../cadoptions) للعرض حسب الارتفاع. |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | يُنشئ مثيلاً من الفئة [`CadOptions`](../cadoptions) للعرض حسب معامل المقياس. |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | يُنشئ مثيلاً من الفئة [`CadOptions`](../cadoptions) للعرض حسب العرض. |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | يُنشئ مثيلاً من الفئة [`CadOptions`](../cadoptions) للعرض حسب العرض والارتفاع. |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
