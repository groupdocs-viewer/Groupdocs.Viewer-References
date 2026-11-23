---
title: "PdfOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير مستندات PDF."
type: docs
weight: 22
url: /ar/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

يوفر خيارات لتصيير مستندات PDF.


فئة PdfOptions تغلف إعدادات ومعلمات مختلفة يمكن استخدامها
للتحكم في عرض مستندات PDF في مكوّن GroupDocs.Viewer.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/).


مثال على الاستخدام:

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | يُنشئ نسخة جديدة من |
PdfOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | يعطل حماية نسخ المحتوى عند العرض إلى HTML. |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | يعطل حماية نسخ المحتوى عند العرض إلى HTML. |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | يحدد ما إذا كان النص من المصدر يُعرض كصورة في HTML. |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | يضبط ما إذا كان النص من المصدر يُعرض كصورة في HTML. |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | يتحقق مما إذا تم تعطيل تجميع الأحرف للحفاظ على أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة. |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | يضبط الخيار لتعطيل تجميع الأحرف، مما يضمن أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة. |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | يتحقق مما إذا كان عرض النص والرسومات يجب أن يتبع ترتيب z في مستند PDF الأصلي عند العرض إلى HTML. |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | تمكين أو تعطيل عرض النص والرسومات وفقًا لترتيب z-order في مستند PDF الأصلي عند التحويل إلى HTML. |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | يحدد ما إذا كان تحسين الخطوط مفعلاً. |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | يمكّن تحسين الخطوط. |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | يمكّن عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر. |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | يمكّن عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر. |
|
|  | [getImageQuality()](#getImageQuality--) | يسترجع جودة الصورة الناتجة للموارد الصورة عند التحويل إلى HTML. |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | يضبط جودة الصورة الناتجة للموارد الصورة عند التحويل إلى HTML. |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة. |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة. |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج. |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج. |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | عطّل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | اضبط العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


يُنشئ نسخة جديدة من
PdfOptions
الفئة.


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


يعطل حماية نسخ المحتوى عند العرض إلى HTML.


عند تحويل ملفات PDF المحمية من نسخ النص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML 'inert' إلى وسم HTML BODY.
القيمة الافتراضية لهذا الخيار هي
false
.


للحصول على مثال شفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


يعطل حماية نسخ المحتوى عند العرض إلى HTML.


عند تحويل ملفات PDF المحمية من نسخ النص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML 'inert' إلى وسم HTML BODY.
القيمة الافتراضية لهذا الخيار هي
false
.


للحصول على مثال شفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


يحدد ما إذا كان النص من المصدر يُعرض كصورة في HTML.


عند ضبط هذا الخيار على
true
، يتم عرض النص كصورة في HTML الناتج.
فعّل هذا الخيار لجعل النص غير قابل للتحديد أو لإصلاح عرض الأحرف وجعل HTML يبدو كـ PDF.
هذا الخيار مدعوم عند التحويل إلى HTML.


***Note:** The default value is 
false
.*


**Returns:**
منطقي -  true  إذا تم عرض النص كصورة في HTML،  false  خلاف ذلك.

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


يضبط ما إذا كان النص من المصدر يُعرض كصورة في HTML.


عند ضبط هذا الخيار على
true
، يتم عرض النص كصورة في HTML الناتج.
فعّل هذا الخيار لجعل النص غير قابل للتحديد أو لإصلاح عرض الأحرف وجعل HTML يبدو كـ PDF.
هذا الخيار مدعوم عند التحويل إلى HTML.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  لتحويل النص إلى صورة في HTML،  false  خلاف ذلك. |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


يتحقق مما إذا تم تعطيل تجميع الأحرف للحفاظ على أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة.
عند تمكين هذا الخيار، يتم عرض الأحرف دون أي تجميع، مما يضمن أقصى دقة.


***Note:** By default, character grouping is enabled.*
عند تحويل ملفات PDF، يقوم GroupDocs.Viewer بتجميع الأحرف الفردية إلى كلمات لتحسين أداء العرض. إذا كان مستندك يحتوي على رموز هيروغليفية أو رموز خاصة، قد ترغب في منع تجميع الأحرف لضمان تخطيط أكثر دقة. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Returns:**
boolean -  true  إذا كان تجميع الأحرف معطلاً،  false  خلاف ذلك.

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


يضبط الخيار لتعطيل تجميع الأحرف، مما يضمن أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة.
عند تمكين هذا الخيار عن طريق ضبط القيمة إلى
true
، يتم تعطيل تجميع الأحرف، مما يضمن أقصى دقة.


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
عند تحويل ملفات PDF، يقوم GroupDocs.Viewer بتجميع الأحرف الفردية إلى كلمات لتحسين أداء العرض. إذا كان مستندك يحتوي على رموز هيروغليفية أو رموز خاصة، قد ترغب في منع تجميع الأحرف لضمان تخطيط أكثر دقة. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتعطيل تجميع الأحرف،  false  لتمكينه. |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


يتحقق مما إذا كان عرض النص والرسومات يجب أن يتبع ترتيب z في مستند PDF الأصلي عند العرض إلى HTML.
عند تمكين هذا الخيار عن طريق إرجاع
true
، يتم عرض النص والرسومات وفقًا لترتيبها z-order في مستند PDF الأصلي.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
بشكل افتراضي، يقوم GroupDocs.Veiewer بعرض النص والرسومات كطبقة واحدة في HTML. يتيح لك هذا الخيار ترتيب الكائنات بنفس ترتيبها في الملف المصدر. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Returns:**
boolean -  true  إذا كان العرض المتعدد الطبقات مفعلاً،  false  خلاف ذلك.

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


تمكين أو تعطيل عرض النص والرسومات وفقًا لترتيب z-order في مستند PDF الأصلي عند التحويل إلى HTML.


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
بشكل افتراضي، يقوم GroupDocs.Veiewer بعرض النص والرسومات كطبقة واحدة في HTML. يتيح لك هذا الخيار ترتيب الكائنات بنفس ترتيبها في الملف المصدر. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين العرض المتعدد الطبقات،  false  لتعطيله. |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


يحدد ما إذا كان تحسين الخط مفعلاً. تحسين الخط يضبط عرض الخط الخارجي.
هذا الخيار مدعوم فقط لخطوط TrueType (TTF) عند استخدامها في المستند المصدر.


***Note:** This option is supported when rendering into PNG or JPG formats.*
تحسين الخط يضبط طريقة عرض الخط الخارجي. ينطبق فقط على خطوط TTF المستخدمة في المستند المصدر. هذا الخيار متاح للعرض إلى صيغ PNG أو JPG. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Returns:**
boolean -  true  إذا كان تحسين الخط مفعلاً،  false  خلاف ذلك.

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


يفعل تحسين الخط. تحسين الخط يضبط عرض الخط الخارجي وهو مدعوم فقط لخطوط TrueType (TTF) عند استخدامها في المستند المصدر.


***Note:** This option is supported when rendering into PNG or JPG formats.*
تحسين الخط يضبط طريقة عرض الخط الخارجي. ينطبق فقط على خطوط TTF المستخدمة في المستند المصدر. هذا الخيار متاح للعرض إلى صيغ PNG أو JPG. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتفعيل تحسين الخط،  false  لتعطيله. |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


يمكّن عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
بشكل افتراضي، يقوم GroupDocs.Viewer بحساب حجم صفحة الصورة الناتجة لتحسين جودة العرض. قم بتمكين هذا الخيار لضمان أن تكون صفحات الإخراج بنفس حجم صفحات مستند PDF المصدر (بالبكسل). القيمة الافتراضية هي false.
هذا الخيار متاح للعرض إلى صيغ PNG أو JPG.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Returns:**
boolean -  true  إذا كان الخيار مفعلاً،  false  خلاف ذلك.

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


يمكّن عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر.


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
بشكل افتراضي، يقوم GroupDocs.Viewer بحساب حجم صفحة الصورة الناتجة لتحسين جودة العرض. قم بتمكين هذا الخيار لضمان أن تكون صفحات الإخراج بنفس حجم صفحات مستند PDF المصدر (بالبكسل). القيمة الافتراضية هي false.
هذا الخيار متاح للعرض إلى صيغ PNG أو JPG.
للحصول على مثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true لتفعيل العرض بالحجم الأصلي للصفحة، false خلاف ذلك. |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


يسترجع جودة الصورة الناتجة لموارد الصور عند العرض إلى HTML. القيمة الافتراضية هي Low.


عند تعيين هذا الخيار إلى true، يقوم GroupDocs.Viewer بعرض النص كصورة في مخرجات HTML. يجعل ذلك النص غير قابل للتحديد ويعزز عرض الأحرف، مما يضمن مظهرًا شبيهًا بـ PDF في HTML. القيمة الافتراضية هي false.
هذا الخيار متاح للعرض إلى HTML.
للحصول على مثال شفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


يضبط جودة الصورة الناتجة لموارد الصور عند العرض إلى HTML. القيمة الافتراضية هي Low.


عند تعيين هذا الخيار إلى true، يقوم GroupDocs.Viewer بعرض النص كصورة في مخرجات HTML. يجعل ذلك النص غير قابل للتحديد ويعزز عرض الأحرف، مما يضمن مظهرًا شبيهًا بـ PDF في HTML. القيمة الافتراضية هي false.
هذا الخيار متاح للعرض إلى HTML.
للحصول على مثال شفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | جودة الصورة الناتجة لموارد الصور عند العرض إلى HTML. |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة.
لضمان أن مخرجات HTML تبدو كما هو PDF المصدر، يتم عرض المستندات إلى HTML بتخطيط ثابت بشكل افتراضي.
عند العرض بتخطيط ثابت، يكون حجم HTML الناتج ثابتًا بحيث تبقى العناصر في نفس المكان بغض النظر عن حجم النافذة.
للعرض إلى HTML بتخطيط سائل، اضبط هذه الخاصية إلى false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
يتم في البداية عرض مستندات PDF و EPUB إلى HTML بتخطيط ثابت للحفاظ على مظهر المستند الأصلي. يعني هذا التخطيط الثابت أن جميع عناصر HTML لها مواقع دقيقة داخل حاوية ذات حجم محدد. تغيير حجم نافذة المتصفح لا يؤثر على موضع وحجم العناصر في المستند.
هذا الخيار متاح فقط عند العرض إلى HTML. القيمة الافتراضية هي true. للعرض بتخطيط سائل، اضبط هذه الخاصية إلى false.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
منطقي - true إذا كان تخطيطًا ثابتًا

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة.
لضمان أن مخرجات HTML تبدو كما هو PDF المصدر، يتم عرض المستندات إلى HTML بتخطيط ثابت بشكل افتراضي.
عند العرض بتخطيط ثابت، يكون حجم HTML الناتج ثابتًا بحيث تبقى العناصر في نفس المكان بغض النظر عن حجم النافذة.
للعرض إلى HTML بتخطيط سائل، اضبط هذه الخاصية إلى false.


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
يتم في البداية عرض مستندات PDF و EPUB إلى HTML بتخطيط ثابت للحفاظ على مظهر المستند الأصلي. يعني هذا التخطيط الثابت أن جميع عناصر HTML لها مواقع دقيقة داخل حاوية ذات حجم محدد. تغيير حجم نافذة المتصفح لا يؤثر على موضع وحجم العناصر في المستند.
هذا الخيار متاح فقط عند العرض إلى HTML. القيمة الافتراضية هي true. للعرض بتخطيط سائل، اضبط هذه الخاصية إلى false.


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fixedLayout | boolean | true إذا كان تخطيطًا ثابتًا |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج.


هذا الخيار مدعوم عند عرض [تنسيقات ملفات PDF وتخطيط الصفحات](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) إلى HTML مع موارد مدمجة وخارجية.


بشكل افتراضي، عند العرض إلى ملفات PDF وتخطيط الصفحات، يتم عرض جميع الصور كصورة PNG واحدة. تُستخدم صورة PNG المرسومة كخلفية لمستند HTML الناتج.


المزيد من المعلومات:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
منطقي -  true إذا تم تغليف الصور في SVG،  false خلاف ذلك.

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج.


هذا الخيار مدعوم عند عرض [تنسيقات ملفات PDF وتخطيط الصفحات](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) إلى HTML مع موارد مدمجة وخارجية.


بشكل افتراضي، عند العرض إلى ملفات PDF وتخطيط الصفحات، يتم عرض جميع الصور كصورة PNG واحدة. تُستخدم صورة PNG المرسومة كخلفية لمستند HTML الناتج.


المزيد من المعلومات:

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true إذا كان يجب تغليف الصور في SVG، false خلاف ذلك. |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص.


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | analyzeFonts | boolean | true إذا كان يجب عرض الخطوط، false خلاف ذلك. |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


عطّل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.


العديد من العمليات مع الخط لا يمكن تنفيذها إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.
على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط.
كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها، يعني ذلك أن الشخص الذي يضع هذه العلامة يتحمل كل المسؤولية
عن الانتهاكات المحتملة للترخيص/القانون على نفسه. لذا يتحمل ذلك على مسؤوليته الخاصة. يُنصح بشدة باستخدام
هذه العلامة فقط عندما تكون واثقًا تمامًا أنك لا تنتهك قانون حقوق النشر. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


اضبط العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.


العديد من العمليات مع الخط لا يمكن تنفيذها إذا كانت هذه العمليات محظورة بموجب ترخيص هذا الخط.
على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط.
كن حذرًا عند استخدام هذه العلامة. عندما يتم تعيينها، يعني ذلك أن الشخص الذي يضع هذه العلامة يتحمل كل المسؤولية
عن الانتهاكات المحتملة للترخيص/القانون على نفسه. لذا يتحمل ذلك على مسؤوليته الخاصة. يُنصح بشدة باستخدام
هذه العلامة فقط عندما تكون واثقًا تمامًا أنك لا تنتهك قانون حقوق النشر. القيمة الافتراضية هي false.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files).


مثال على الاستخدام:

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

