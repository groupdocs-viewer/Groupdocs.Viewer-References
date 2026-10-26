---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "استخدم هذه الفئة لتحديد خيارات تحسين PDF لتطبيقها على ملف PDF الناتج."
type: docs
weight: 21
url: /ar/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

استخدم هذه الفئة لتحديد خيارات تحسين PDF لتطبيقها على ملف PDF الناتج.

تُدعم خيارات التحسين هذه لأي تنسيقات ملفات إدخال مدعومة للتصدير إلى PDF. للحصول على تفاصيل وعينات من الشيفرة، راجع هذه [page][] وأقسامها الفرعية.

مثال على الاستخدام:

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | يضبط القيم الافتراضية لخيار MaxResolution إلى 300 وخيار ImageQuality إلى 100. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isLinearize()](#isLinearize--) | يُمكّن تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب. |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | يحدد ما إذا كان سيتم تحسين ملف PDF الناتج للتصفح عبر الإنترنت باستخدام متصفح ويب. |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | يمكن حذف التعليقات التوضيحية عندما تكون غير ضرورية. |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | يحدد ما إذا كان سيتم إزالة التعليقات التوضيحية غير الضرورية من ملف PDF. |
| [isRemoveFormFields()](#isRemoveFormFields--) | إذا كان مستند PDF يحتوي على نماذج AcroForms، يمكننا محاولة تقليل حجم الملف عن طريق تسوية حقول النموذج. |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | يحدد ما إذا كان سيتم إزالة حقول النموذج من ملف PDF. |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | يتكوّن ملف PDF من نص، صورة، مرفق، تعليقات توضيحية، رسومات وكائنات أخرى. |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | يحدد ما إذا كان سيتم تحويل ملف PDF إلى تدرج الرمادي. |
| [isSubsetFonts()](#isSubsetFonts--) | كل خط يُستخدم لعرض النص على الصفحة يحتوي على مجموعة من الرموز للأحرف. |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | يحدد ما إذا كان سيتم تقسيم الخطوط إلى مجموعات فرعية في ملف PDF. |
| [isCompressImages()](#isCompressImages--) | إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وتحديد جودتها. |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | يحدد ما إذا كان سيتم ضغط الصور في ملف PDF. |
| [getImageQuality()](#getImageQuality--) | إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وتحديد جودتها. |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | يحدد جودة الصورة لضغط الصور في ملف PDF. |
| [isResizeImages()](#isResizeImages--) | يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | يحدد ما إذا كان سيتم تغيير حجم الصور في ملف PDF. |
| [getMaxResolution()](#getMaxResolution--) | يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | يحدد الحد الأقصى للدقة لتغيير حجم الصور في ملف PDF. |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | تحسين حدود جداول Excel والخطوط للحصول على حجم ملف ناتج أصغر. |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | يحدد ما إذا كان سيتم تحسين جداول البيانات في ملف PDF. |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | إزالة المعلومات الخاصة (معلومات جزء الصفحة) إذا تم تعيينها إلى true. |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | يحدد ما إذا كان سيتم إزالة المعلومات الخاصة من ملف PDF. |
| [isUnembedFonts()](#isUnembedFonts--) | إذا كان المستند يستخدم خطوطًا مدمجة فهذا يعني أن جميع بيانات الخط موضوعة في المستند. |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | يحدد ما إذا كان سيتم فك دمج الخطوط المدمجة في ملف PDF. |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | أحيانًا يحتوي المستند على عدة تدفقات موارد متطابقة (مثل الصور). |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | يحدد ما إذا كان سيتم ربط التدفقات المكررة في ملف PDF. |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | إذا تم تعيين هذه الخاصية إلى true، فسيتم إعادة استخدام محتوى الصفحة عند تحسين المستند للصفحات المتطابقة. |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | يحدد ما إذا كان يُسمح بإعادة استخدام محتوى الصفحة في ملف PDF. |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | أحيانًا يحتوي المستند على تدفقات موارد غير مستخدمة. |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | يحدد ما إذا كان يجب إزالة التدفقات غير المستخدمة من ملف PDF. |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | أحيانًا يحتوي مستند PDF على كائنات PDF لا يتم الإشارة إليها من أي كائن آخر في المستند. |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | يحدد ما إذا كان يجب إزالة الكائنات غير المستخدمة من ملف PDF. |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


يضبط القيم الافتراضية لخيار MaxResolution إلى 300 وخيار ImageQuality إلى 100.

للتفاصيل وعينات الشيفرة، راجع هذه [page][] وأبنائها.


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


يُمكّن تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب.

للحصول على مثال على الشيفرة، راجع هذه [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
منطقي -  true  إذا كان ملف PDF الناتج مُحسّن للتصفح عبر الإنترنت،  false  خلاف ذلك.
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


يحدد ما إذا كان سيتم تحسين ملف PDF الناتج للتصفح عبر الإنترنت باستخدام متصفح ويب.

للحصول على مثال على الشيفرة، راجع هذه [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linearize | boolean | true  لتحسين ملف PDF الناتج للتصفح عبر الإنترنت،  false  خلاف ذلك. |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


يمكن حذف التعليقات التوضيحية عندما تكون غير ضرورية. عندما تكون مطلوبة ولكن لا تحتاج إلى تحرير إضافي، يمكن تسويتها. سيؤدي ذلك إلى تقليل حجم الملف.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
منطقي -  true  إذا تم إزالة التعليقات التوضيحية،  false  خلاف ذلك.
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


يحدد ما إذا كان سيتم إزالة التعليقات التوضيحية غير الضرورية من ملف PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeAnnotations | boolean | true  لإزالة التعليقات التوضيحية غير الضرورية،  false  خلاف ذلك. |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


إذا كان مستند PDF يحتوي على نماذج AcroForms، يمكننا محاولة تقليل حجم الملف عن طريق تسوية حقول النموذج.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
منطقي -  true  إذا تم إزالة حقول النموذج،  false  خلاف ذلك.
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


يحدد ما إذا كان سيتم إزالة حقول النموذج من ملف PDF.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeFormFields | boolean | true  لإزالة حقول النموذج،  false  خلاف ذلك. |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


يتكون ملف PDF من نص، صورة، مرفق، تعليقات توضيحية، رسومات وكائنات أخرى. قد تواجه حاجة لتحويل PDF من مساحة ألوان RGB إلى تدرج الرمادي لتسريع عملية طباعة تلك الملفات. كما أن تحويل الملف إلى تدرج الرمادي يقلل من حجم المستند، لكن هذا التغيير قد يؤدي إلى انخفاض جودة المستند. حاليًا، تدعم هذه الميزة ميزة Pre-Flight في Adobe Acrobat.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
منطقي -  true  إذا تم تحويل PDF إلى تدرج الرمادي،  false  خلاف ذلك.
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


يحدد ما إذا كان سيتم تحويل ملف PDF إلى تدرج الرمادي.

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| convertToGrayScale | boolean | true  لتحويل PDF إلى تدرج الرمادي،  false  خلاف ذلك. |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


كل خط يُستخدم لعرض النص على الصفحة يحتوي على مجموعة من الرموز (glyphs) لأحرف الخط. تدعم مواصفة PDF مفهوم \"تقسيم الخط\" أي خط يحتوي فقط على الرموز المستخدمة. قد يسبب ذلك مشاكل عندما يحتاج النص إلى تحديث (لأن الرموز المطلوبة قد تكون غير موجودة في الخط)، ولكن بالنسبة للمستند الذي لا يُخطط لتغييره يسمح ذلك بتقليل الحجم.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
منطقي -  true  إذا تم تقسيم الخطوط،  false  خلاف ذلك.
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


يحدد ما إذا كان سيتم تقسيم الخطوط إلى مجموعات فرعية في ملف PDF.

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| subsetFonts | boolean | true  لتقسيم الخطوط،  false  خلاف ذلك. |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وضبط جودتها. لتمكين ضغط الصور، اضبط هذا الخيار على true. سيتم إعادة ضغط جميع الصور في المستند. يتم تعريف الضغط بواسطة خاصية ImageQuality، التي تمثل قيمة الجودة بالنسبة المئوية. 100% تعني جودة غير متغيرة. لتقليل جودة الصورة، اضبط خاصية ImageQuality إلى أقل من 100.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
منطقي -  true  إذا تم ضغط الصور،  false  وإلا.
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


يحدد ما إذا كان سيتم ضغط الصور في ملف PDF.

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| compressImages | boolean | true  لتضغط الصور،  false  وإلا. |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وضبط جودتها. لتمكين ضغط الصور، اضبط خيار CompressImages على true. سيتم إعادة ضغط جميع الصور في المستند. يتم تعريف الضغط بواسطة خاصية ImageQuality، التي تمثل قيمة الجودة بالنسبة المئوية. 100% تعني جودة غير متغيرة. لتقليل جودة الصورة، اضبط خيار CompressImages على true وخاصية ImageQuality إلى أقل من 100.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - جودة الصورة (القيمة بين 1 و 100).
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


يحدد جودة الصورة لضغط الصور في ملف PDF.

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageQuality | int | جودة الصورة (القيمة بين 1 و 100). |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. في هذه الحالة، يجب ضبط CompressImage على true، وResizeImages على true، وMaxResolution على القيمة المناسبة.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
منطقي -  true  إذا تم تغيير حجم الصور،  false  وإلا.
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


يحدد ما إذا كان سيتم تغيير حجم الصور في ملف PDF.

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resizeImages | boolean | true  لتغيير حجم الصور،  false  وإلا. |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. في هذه الحالة، يجب ضبط CompressImage على true، وResizeImages على true، وMaxResolution على القيمة المناسبة.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - أقصى دقة للصور.
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


يحدد الحد الأقصى للدقة لتغيير حجم الصور في ملف PDF.

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxResolution | int | أقصى دقة للصور. |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


تحسين حدود جداول Excel والخطوط للحصول على حجم ملف ناتج أصغر.

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
منطقي -  true  إذا تم تحسين جداول البيانات،  false  وإلا.
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


يحدد ما إذا كان سيتم تحسين جداول البيانات في ملف PDF.

للحصول على مثال على الشيفرة، راجع هذه [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  لتحسين جداول البيانات،  false  وإلا. |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


إزالة المعلومات الخاصة (معلومات جزء الصفحة) إذا تم تعيينها إلى true.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم إزالة المعلومات الخاصة،  false  وإلا.
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


يحدد ما إذا كان سيتم إزالة المعلومات الخاصة من ملف PDF.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removePrivateInfo | boolean | true  لإزالة المعلومات الخاصة،  false  وإلا. |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


إذا كان المستند يستخدم خطوطًا مضمنة فهذا يعني أن جميع بيانات الخط موضوعة في المستند. الميزة هي أن المستند يمكن عرضه بغض النظر عما إذا كان الخط مثبتًا على جهاز المستخدم أم لا. لكن تضمين الخطوط يجعل المستند أكبر. طريقة unembed fonts تزيل جميع الخطوط المضمنة. هذا يقلل من حجم المستند لكن قد يصبح المستند غير قابل للقراءة إذا لم يتم تثبيت الخط الصحيح.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم إلغاء تضمين الخطوط،  false  وإلا.
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


يحدد ما إذا كان سيتم فك دمج الخطوط المدمجة في ملف PDF.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| unembedFonts | boolean | true  لإلغاء تضمين الخطوط المضمنة،  false  وإلا. |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


أحيانًا يحتوي المستند على عدة تدفقات موارد متطابقة (على سبيل المثال الصور). قد يحدث هذا، على سبيل المثال، عندما يتم ربط المستند بنفسه. يحتوي المستند الناتج على نسختين مستقلتين من نفس تدفق المورد. نقوم بتحليل جميع تدفقات الموارد ومقارنتها. إذا تكررت التدفقات يتم دمجها، أي يبقى نسخة واحدة فقط، ويتم تعديل المراجع وفقًا لذلك وإزالة نسخ الكائن. أحيانًا يؤدي ذلك إلى تقليل حجم المستند.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم ربط تدفقات مكررة،  false  غير ذلك.
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


يحدد ما إذا كان سيتم ربط التدفقات المكررة في ملف PDF.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  لربط التدفقات المكررة،  false  غير ذلك. |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


إذا تم تعيين هذه الخاصية إلى true، فسيتم إعادة استخدام محتوى الصفحة عند تحسين المستند للصفحات المتطابقة.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم إعادة استخدام محتوى الصفحة،  false  غير ذلك.
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


يحدد ما إذا كان يُسمح بإعادة استخدام محتوى الصفحة في ملف PDF.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| allowReusePageContent | boolean | true  للسماح بإعادة استخدام محتوى الصفحة،  false  غير ذلك. |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


أحيانًا يحتوي المستند على تدفقات موارد غير مستخدمة. هذه التدفقات ليست \u201cunused objects\u201d لأنها مُشار إليها من قاموس موارد الصفحة. قد يحدث هذا في الحالات التي تمت فيها إزالة صورة من الصفحة ولكن لم تُحذف من موارد الصفحة. أيضًا، غالبًا ما يحدث هذا عندما يتم استخراج الصفحات من المستند وتكون صفحات المستند لديها موارد \u201ccommon\u201d، أي نفس كائن Resources. يتم تحليل محتويات الصفحة لتحديد ما إذا كان تدفق المورد مستخدمًا أم لا. تُحذف التدفقات غير المستخدمة. أحيانًا يؤدي ذلك إلى تقليل حجم المستند.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم إزالة التدفقات غير المستخدمة،  false  غير ذلك.
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


يحدد ما إذا كان يجب إزالة التدفقات غير المستخدمة من ملف PDF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  لإزالة التدفقات غير المستخدمة،  false  غير ذلك. |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


أحيانًا يحتوي مستند PDF على كائنات PDF غير مُشار إليها من أي كائن آخر في المستند. قد يحدث هذا، على سبيل المثال، عندما تُزال صفحة من شجرة صفحات المستند لكن كائن الصفحة نفسه لا يُزال. إزالة هذه الكائنات لا تجعل المستند غير صالح بل يقلل حجمه.

***Note:** The default value is  false .*

**Returns:**
منطقي -  true  إذا تم إزالة الكائنات غير المستخدمة،  false  غير ذلك.
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


يحدد ما إذا كان يجب إزالة الكائنات غير المستخدمة من ملف PDF.

***Note:** The default value is  false .*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  لإزالة الكائنات غير المستخدمة،  false  غير ذلك. |

