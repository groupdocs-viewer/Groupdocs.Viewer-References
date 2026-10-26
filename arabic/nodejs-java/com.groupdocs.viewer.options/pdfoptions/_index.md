---
title: "PdfOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض مستندات PDF."
type: docs
weight: 22
url: /ar/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

يوفر خيارات لعرض مستندات PDF.

فئة PdfOptions تضم إعدادات ومعلمات مختلفة يمكن استخدامها للتحكم في عرض مستندات PDF في مكوّن GroupDocs.Viewer. للحصول على التفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | يُنشئ مثيلًا جديدًا من فئة PdfOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | يعطل حماية نسخ المحتوى عند التحويل إلى HTML. |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | يعطل حماية نسخ المحتوى عند التحويل إلى HTML. |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | يحدد ما إذا كان النص من المصدر يُعرض كصورة في HTML. |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | يضبط ما إذا كان النص من المصدر يُعرض كصورة في HTML. |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | يتحقق مما إذا تم تعطيل تجميع الأحرف للحفاظ على أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة. |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | يضبط الخيار لتعطيل تجميع الأحرف، مما يضمن أقصى دقة أثناء تموضع الأحرف عند عرض الصفحة. |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | يتحقق مما إذا كان عرض النص والرسومات يجب أن يتبع ترتيب z في مستند PDF الأصلي عند التحويل إلى HTML. |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | يفعل أو يعطل عرض النص والرسومات وفقًا لترتيب z في مستند PDF الأصلي عند التحويل إلى HTML. |
| [isEnableFontHinting()](#isEnableFontHinting--) | يحدد ما إذا كان تحسين الخطوط مفعلاً. |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | يفعل تحسين الخطوط. |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | يفعل عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر. |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | يفعل عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر. |
| [getImageQuality()](#getImageQuality--) | يسترجع جودة الصورة الناتجة للموارد الصورة عند التحويل إلى HTML. |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | يضبط جودة الصورة الناتجة للموارد الصورة عند التحويل إلى HTML. |
| [isFixedLayout()](#isFixedLayout--) | PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة. |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF هو تنسيق ثابت لذا جميع العناصر لها موضع محدد على الصفحة. |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج. |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج. |
| [isFixLinkIssue()](#isFixLinkIssue--) | يحاول إصلاح المشكلة عندما يكون محتوى صفحة HTML بالكامل رابطًا. |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | يحاول إصلاح المشكلة عندما يكون محتوى صفحة HTML بالكامل رابطًا. |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | يستبدل الخطوط حسب الحاجة لضمان عرض جميع الأحرف في النص. |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | عطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | قم بتعيين العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي. |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


يُنشئ مثيلًا جديدًا من فئة PdfOptions.

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


يعطل حماية نسخ المحتوى عند التحويل إلى HTML.

عند تحويل ملفات PDF المحمية من نسخ النصوص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML 'inert' إلى وسم HTML BODY. القيمة الافتراضية لهذا الخيار هي false.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


يعطل حماية نسخ المحتوى عند التحويل إلى HTML.

عند تحويل ملفات PDF المحمية من نسخ النصوص والصور إلى HTML، يضيف GroupDocs.Viewer سمة HTML 'inert' إلى وسم HTML BODY. القيمة الافتراضية لهذا الخيار هي false.

للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


يحدد ما إذا كان النص من المصدر يُعرض كصورة في HTML.

عند تعيين هذا الخيار إلى true، يتم عرض النص كصورة في HTML الناتج. فعّل هذا الخيار لجعل النص غير قابل للتحديد أو لإصلاح عرض الأحرف وجعل HTML يبدو كملف PDF. هذا الخيار مدعوم عند التحويل إلى HTML.

***Note:** The default value is  false .*

**Returns:**
boolean - true إذا تم عرض النص كصورة في HTML، false خلاف ذلك.
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


يضبط ما إذا كان النص من المصدر يُعرض كصورة في HTML.

عند تعيين هذا الخيار إلى true، يتم عرض النص كصورة في HTML الناتج. فعّل هذا الخيار لجعل النص غير قابل للتحديد أو لإصلاح عرض الأحرف وجعل HTML يبدو كملف PDF. هذا الخيار مدعوم عند التحويل إلى HTML.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderTextAsImage | boolean | true لعرض النص كصورة في HTML، false خلاف ذلك. |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


يتحقق مما إذا تم تعطيل تجميع الأحرف للحفاظ على أقصى دقة أثناء تموضع الأحرف عند تحويل الصفحة. عند تمكين هذا الخيار، يتم عرض الأحرف بدون أي تجميع، مما يضمن أقصى دقة.

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
boolean - true إذا كان تجميع الأحرف معطلاً، false خلاف ذلك.
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


يضبط الخيار لتعطيل تجميع الأحرف، مما يضمن أقصى دقة أثناء تموضع الأحرف عند تحويل الصفحة. عند تمكين هذا الخيار بتعيين القيمة إلى true، يتم تعطيل تجميع الأحرف، مما يضمن أقصى دقة.

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true لتعطيل تجميع الأحرف، false لتمكينه. |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


يتحقق مما إذا كان ينبغي أن يتبع عرض النص والرسومات ترتيب z في مستند PDF الأصلي عند التحويل إلى HTML. عند تمكين هذا الخيار بإرجاع true، يتم عرض النص والرسومات وفقًا لترتيب z في مستند PDF الأصلي.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
boolean - true إذا كان العرض الطبقي مفعلاً، false خلاف ذلك.
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


يفعل أو يعطل عرض النص والرسومات وفقًا لترتيب z في مستند PDF الأصلي عند التحويل إلى HTML.

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true لتمكين العرض الطبقي، false لتعطيله. |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


يحدد ما إذا كان تحسين الخط مفعلاً. تحسين الخط يضبط عرض الخط القائم على المخطط. هذا الخيار مدعوم فقط لخطوط TrueType (TTF) عند استخدامها في المستند المصدر.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
boolean - true إذا كان تحسين الخط مفعلاً، false خلاف ذلك.
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


يفعل تحسين الخط. تحسين الخط يضبط عرض الخط القائم على المخطط وهو مدعوم فقط لخطوط TrueType (TTF) عند استخدامها في المستند المصدر.

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true لتفعيل تحسين الخط، false لتعطيله. |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


يفعل عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
boolean - true إذا كان الخيار مفعلاً، false خلاف ذلك.
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


يفعل عرض الصفحات بنفس الحجم بالبكسل كما هو حجم الصفحة في مستند PDF المصدر.

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true لتمكين العرض بالحجم الأصلي للصفحة، false خلاف ذلك. |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


يسترجع جودة الصورة الناتجة لموارد الصور عند التحويل إلى HTML. القيمة الافتراضية هي Low.

عند تعيين هذا الخيار إلى true، يقوم GroupDocs.Viewer بعرض النص كصورة في مخرجات HTML. يجعل ذلك النص غير قابل للتحديد ويحسن عرض الأحرف، مما يضمن مظهرًا شبيهًا بـ PDF في HTML. القيمة الافتراضية هي false. هذا الخيار متاح للتحويل إلى HTML. للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


يضبط جودة الصورة الناتجة لموارد الصور عند التحويل إلى HTML. القيمة الافتراضية هي Low.

عند تعيين هذا الخيار إلى true، يقوم GroupDocs.Viewer بعرض النص كصورة في مخرجات HTML. يجعل ذلك النص غير قابل للتحديد ويحسن عرض الأحرف، مما يضمن مظهرًا شبيهًا بـ PDF في HTML. القيمة الافتراضية هي false. هذا الخيار متاح للتحويل إلى HTML. للحصول على مثال شفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | جودة الصورة الناتجة لموارد الصور عند التحويل إلى HTML. |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF هو تنسيق ثابت لذا جميع العناصر لها موقع محدد على الصفحة. لضمان أن يكون HTML الناتج مماثلاً للـ PDF الأصلي، يتم تحويل المستندات إلى HTML بتخطيط ثابت بشكل افتراضي. عند التحويل بتخطيط ثابت يكون حجم HTML الناتج ثابتًا بحيث تبقى العناصر في نفس الموقع بغض النظر عن حجم النافذة. لتحويل إلى HTML بتخطيط مرن، اضبط هذه الخاصية على false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
منطقي - true إذا كان تخطيطًا ثابتًا
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF هو تنسيق ثابت لذا جميع العناصر لها موقع محدد على الصفحة. لضمان أن يكون HTML الناتج مماثلاً للـ PDF الأصلي، يتم تحويل المستندات إلى HTML بتخطيط ثابت بشكل افتراضي. عند التحويل بتخطيط ثابت يكون حجم HTML الناتج ثابتًا بحيث تبقى العناصر في نفس الموقع بغض النظر عن حجم النافذة. لتحويل إلى HTML بتخطيط مرن، اضبط هذه الخاصية على false.

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fixedLayout | boolean | true إذا كان تخطيطًا ثابتًا |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج.

هذا الخيار مدعوم عند تحويل [PDF and Page Layout file formats][] إلى HTML مع موارد مدمجة وخارجية.

بشكل افتراضي، عند التحويل إلى ملفات PDF وPage Layout، يتم تحويل جميع الصور إلى صورة PNG واحدة. تُستخدم صورة PNG المُحوَّلة كخلفية للمستند HTML الناتج.

المزيد من المعلومات:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
منطقي -  true إذا تم تغليف الصور بـ SVG،  false خلاف ذلك.
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


فعّل هذا الخيار لتغليف كل صورة في مستند HTML الناتج بوسم SVG لتحسين جودة الإخراج.

هذا الخيار مدعوم عند تحويل [PDF and Page Layout file formats][] إلى HTML مع موارد مدمجة وخارجية.

بشكل افتراضي، عند التحويل إلى ملفات PDF وPage Layout، يتم تحويل جميع الصور إلى صورة PNG واحدة. تُستخدم صورة PNG المُحوَّلة كخلفية للمستند HTML الناتج.

المزيد من المعلومات:

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| wrapImagesInSvg | boolean | true إذا كان يجب تغليف الصور بـ SVG، false خلاف ذلك. |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


يحاول إصلاح المشكلة عندما يكون محتوى صفحة HTML بالكامل رابطًا. يعمل فقط عندما يكون تنسيق الإدخال PDF وتنسيق الإخراج HTML (مع موارد مدمجة أو خارجية). بشكل افتراضي يكون معطَّلًا (false). فعِّله فقط عندما تعرف ما تقوم به ولماذا. تشغيل هذا الخيار يزيد من زمن معالجة المستند.

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


يحاول إصلاح المشكلة عندما يكون محتوى صفحة HTML بالكامل رابطًا. يعمل فقط عندما يكون تنسيق الإدخال PDF وتنسيق الإخراج HTML (مع موارد مدمجة أو خارجية). بشكل افتراضي يكون معطَّلًا (false). فعِّله فقط عندما تعرف ما تقوم به ولماذا. تشغيل هذا الخيار يزيد من زمن معالجة المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fixLinkIssue | boolean | true إذا كان يجب إصلاح المشكلة، false خلاف ذلك. |

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
| analyzeFonts | boolean | true إذا كان يجب عرض الخطوط، false خلاف ذلك. |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


عطل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.

العديد من العمليات المتعلقة بالخط لا يمكن تنفيذها إذا كانت محظورة بموجب ترخيص هذا الخط. على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. كن حذرًا عند استخدام هذه العلامة. عندما يتم تفعيلها، يعني ذلك أن الشخص الذي يفعّلها يتحمل كامل المسؤولية عن أي انتهاكات محتملة للترخيص أو القانون. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون متأكدًا تمامًا من أنك لا تنتهك قانون حقوق النشر. بشكل افتراضي false. للحصول على مثال على الشيفرة، راجع [documentation][].

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


قم بتعيين العلامة لتعطيل أي قيود ترخيص لجميع الخطوط في مستند XPS/OXPS الحالي.

العديد من العمليات المتعلقة بالخط لا يمكن تنفيذها إذا كانت محظورة بموجب ترخيص هذا الخط. على سبيل المثال، لا يمكن تضمين بعض الخطوط في مستند PDF إذا كانت قواعد الترخيص تمنع التضمين لهذا الخط. كن حذرًا عند استخدام هذه العلامة. عندما يتم تفعيلها، يعني ذلك أن الشخص الذي يفعّلها يتحمل كامل المسؤولية عن أي انتهاكات محتملة للترخيص أو القانون. لذا يتحمل المخاطرة بنفسه. يُنصح بشدة باستخدام هذه العلامة فقط عندما تكون متأكدًا تمامًا من أنك لا تنتهك قانون حقوق النشر. بشكل افتراضي false. للحصول على مثال على الشيفرة، راجع [documentation][].

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

