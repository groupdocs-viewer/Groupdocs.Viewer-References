---
title: "WordProcessingOptions"
second_title: "مرجع API الخاص بـ GroupDocs.Viewer لـ .NET"
description: "يحتوي على خيارات لعرض مستندات Word. لمزيد من التفاصيل راجع الوثائق https//docs.groupdocs.com/viewer/net/renderworddocuments/."
type: docs
weight: 630
url: /ar/net/groupdocs.viewer.options/wordprocessingoptions/
---

## WordProcessingOptions class

يحتوي على خيارات عرض مستندات Word. للحصول على تفاصيل، راجع [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/).

```csharp
public class WordProcessingOptions : ICloneable, IEquatable<WordProcessingOptions>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [WordProcessingOptions](wordprocessingoptions)() | يحتوي على خيارات لعرض مستندات معالجة النصوص. لمزيد من التفاصيل، راجع [documentation](https://docs.groupdocs.com/viewer/net/render-word-documents/). |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/wordprocessingoptions/bottommargin) { get; set; } | يضبط الهامش السفلي للصفحة. |
| [EnableOpenTypeFeatures](../../groupdocs.viewer.options/wordprocessingoptions/enableopentypefeatures) { get; set; } | هذا الخيار يتيح ضبط التباعد بين الحروف وغيرها من ميزات OpenType عند عرض النصوص العربية أو العبرية أو الهندية المستندة إلى اللاتينية أو السيريالية. |
| [HorizontalResolution](../../groupdocs.viewer.options/wordprocessingoptions/horizontalresolution) { get; set; } | يحصل أو يعيّن الدقة الأفقية للصور المُولَّدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند عرض مستندات WordProcessing إلى صيغ PNG أو JPEG فقط. |
| [LeftMargin](../../groupdocs.viewer.options/wordprocessingoptions/leftmargin) { get; set; } | يعيّن الهامش الأيسر للصفحة. |
| [PageNumberLocation](../../groupdocs.viewer.options/wordprocessingoptions/pagenumberlocation) { get; set; } | يسمح بفرض تطبيق ترقيم الصفحات للمستند WordProcessing المحمَّل. بشكل افتراضي يكون NotApply — المستند يبقى كما هو. |
| [PageSize](../../groupdocs.viewer.options/wordprocessingoptions/pagesize) { get; set; } | حجم صفحة الإخراج. القيمة الافتراضية هي Unspecified مما يعني أن حجم الصفحة المحدد في إعدادات الصفحة (Page Setup) يُستخدم. عند عرض ملفات HTM وHTML تكون حجم الصفحة الافتراضي مضبوطة على Letter 792 × 612 نقطة. نتيجةً لذلك قد لا يتناسب بعض المحتوى مع إطار الصفحة. اضبط حجم صفحة أكبر مثل A3 لتلائم المحتوى. |
| [RenderTrackedChanges](../../groupdocs.viewer.options/wordprocessingoptions/rendertrackedchanges) { get; set; } | يُفعّل عرض التغييرات المتتبعة (المراجعات). |
| [RightMargin](../../groupdocs.viewer.options/wordprocessingoptions/rightmargin) { get; set; } | يعيّن الهامش الأيمن للصفحة. |
| [TopMargin](../../groupdocs.viewer.options/wordprocessingoptions/topmargin) { get; set; } | يعيّن الهامش العلوي للصفحة. |
| [UnlinkTableOfContents](../../groupdocs.viewer.options/wordprocessingoptions/unlinktableofcontents) { get; set; } | عند العرض إلى HTML أو PDF، يمكنك ضبط هذا الخيار إلى `true` لتعطيل التنقل من جدول المحتويات. بالنسبة للعرض HTML، سيتم استبدال وسوم `a` ذات الروابط النسبية بوسوم `span`، مما يزيل الوظيفة لكنه يحافظ على المظهر البصري. بالنسبة للعرض PDF، سيُعرض جدول المحتويات كنص عادي دون روابط إلى أقسام المستند. |
| [UpdateFields](../../groupdocs.viewer.options/wordprocessingoptions/updatefields) { get; set; } | يحصل أو يعيّن قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند WordProcessing المدخل إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية لهذه الخاصية هي `true` — سيتم تحديث الحقول قبل الحفظ. |
| [VerticalResolution](../../groupdocs.viewer.options/wordprocessingoptions/verticalresolution) { get; set; } | يحصل أو يعيّن الدقة العمودية للصور المُولَّدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند عرض مستندات WordProcessing إلى صيغ PNG أو JPEG فقط. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../groupdocs.viewer.options/wordprocessingoptions/clone)() | ينشئ ويعيد نسخة عميقة كاملة من هذه الخيارات |
| [Equals](../../groupdocs.viewer.options/wordprocessingoptions/equals#equals)(WordProcessingOptions) | يحدد ما إذا كانت المثيلة المحددة من [`WordProcessingOptions`](../wordprocessingoptions) مساوية لهذا |

### انظر أيضًا

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- لا تقم بالتعديل: تم إنشاؤه بواسطة xmldocmd لـ GroupDocs.Viewer.dll -->
