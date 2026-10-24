---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "استخدم هذه الفئة لتحديد خيارات تحسين PDF لتطبيقها على ملف PDF الناتج."
type: docs
weight: 21
url: /ar/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

استخدم هذه الفئة لتحديد خيارات تحسين PDF لتطبيقها على ملف PDF الناتج.


هذه الخيارات التحسينية مدعومة لأي صيغ ملفات إدخال مدعومة للتصدير إلى PDF.
للتفاصيل وعينات الشيفرة، راجع هذه [الصفحة](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) وملحقاتها.


مثال على الاستخدام:

````

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
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | يضبط القيم الافتراضية لخيار MaxResolution إلى 300 وخيار ImageQuality إلى 100. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | يفعل تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب. |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | يضبط ما إذا كان يجب تحسين ملف PDF الناتج للتصفح عبر الإنترنت باستخدام متصفح ويب. |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | يمكن حذف التعليقات التوضيحية عندما تكون غير ضرورية. |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | يضبط ما إذا كان يجب إزالة التعليقات التوضيحية غير الضرورية من ملف PDF. |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | إذا كان مستند PDF يحتوي على AcroForms، يمكننا محاولة تقليل حجم الملف عن طريق تسوية حقول النموذج. |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | يضبط ما إذا كان يجب إزالة حقول النموذج من ملف PDF. |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | يتكون ملف PDF من نص، صورة، مرفق، تعليقات توضيحية، رسومات وكائنات أخرى. |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | يضبط ما إذا كان يجب تحويل ملف PDF إلى تدرج الرمادي. |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | كل خط يُستخدم لعرض النص على الصفحة يحتوي على مجموعة من الرموز للحروف. |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | يضبط ما إذا كان يجب تقليل مجموعة الخطوط في ملف PDF. |
|
|  | [isCompressImages()](#isCompressImages--) | إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وضبط جودتها. |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | يضبط ما إذا كان يجب ضغط الصور في ملف PDF. |
|
|  | [getImageQuality()](#getImageQuality--) | إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وضبط جودتها. |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | يضبط جودة الصورة لضغط الصور في ملف PDF. |
|
|  | [isResizeImages()](#isResizeImages--) | يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | يحدد ما إذا كان يجب تغيير حجم الصور في ملف PDF. |
|
|  | [getMaxResolution()](#getMaxResolution--) | يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | يحدد أقصى دقة لتغيير حجم الصور في ملف PDF. |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | تحسين حدود خطوط وجداول Excel والخطوط للحصول على حجم ملف أصغر. |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | يحدد ما إذا كان يجب تحسين جداول البيانات في ملف PDF. |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | إزالة المعلومات الخاصة (معلومات جزء الصفحة) إذا تم تعيينها إلى true. |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | يحدد ما إذا كان يجب إزالة المعلومات الخاصة من ملف PDF. |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | إذا كان المستند يستخدم خطوطًا مضمنة فهذا يعني أن جميع بيانات الخطوط موضوعة في المستند. |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | يحدد ما إذا كان يجب فك تضمين الخطوط المضمنة في ملف PDF. |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | أحيانًا يحتوي المستند على عدة تدفقات موارد متطابقة (على سبيل المثال الصور). |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | يحدد ما إذا كان يجب ربط التدفقات المكررة في ملف PDF. |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | إذا تم تعيين هذه الخاصية إلى true، سيتم إعادة استخدام محتوى الصفحة عند تحسين المستند للصفحات المتطابقة. |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | يحدد ما إذا كان يجب السماح بإعادة استخدام محتوى الصفحة في ملف PDF. |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | أحيانًا يحتوي المستند على تدفقات موارد غير مستخدمة. |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | يحدد ما إذا كان يجب إزالة التدفقات غير المستخدمة من ملف PDF. |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | أحيانًا يحتوي مستند PDF على كائنات PDF غير مُشار إليها |
من أي كائن آخر في المستند.
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | يحدد ما إذا كان يجب إزالة الكائنات غير المستخدمة من ملف PDF. |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


يضبط القيم الافتراضية لخيار MaxResolution إلى 300 وخيار ImageQuality إلى 100.


للتفاصيل وعينات الشيفرة، راجع هذه [الصفحة](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) وملحقاتها.


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


يفعل تحسين ملف PDF الناتج للعرض عبر الإنترنت باستخدام متصفح ويب.


للحصول على مثال شفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Returns:**
منطقية -  true  إذا كان ملف PDF الناتج محسّنًا للتصفح عبر الإنترنت،  false  غير ذلك.

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


يضبط ما إذا كان يجب تحسين ملف PDF الناتج للتصفح عبر الإنترنت باستخدام متصفح ويب.


للحصول على مثال شفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | linearize | boolean | true  لتحسين ملف PDF الناتج للتصفح عبر الإنترنت،  false  غير ذلك. |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


يمكن حذف التعليقات التوضيحية عندما تكون غير ضرورية. عندما تكون مطلوبة ولكن لا تحتاج إلى تحرير إضافي، يمكن تسويتها. سيؤدي ذلك إلى تقليل حجم الملف.


***Note:** The default value is 
false
.*
للحصول على مثال شفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Returns:**
منطقية -  true  إذا تم إزالة التعليقات التوضيحية،  false  غير ذلك.

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


يضبط ما إذا كان يجب إزالة التعليقات التوضيحية غير الضرورية من ملف PDF.


***Note:** The default value is 
false
.*
للحصول على مثال شفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | removeAnnotations | boolean | true  لإزالة التعليقات التوضيحية غير الضرورية،  false  خلاف ذلك. |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


إذا كان مستند PDF يحتوي على AcroForms، يمكننا محاولة تقليل حجم الملف عن طريق تسوية حقول النموذج.


***Note:** The default value is 
false
.*
للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Returns:**
منطقي -  true  إذا تم إزالة حقول النموذج،  false  خلاف ذلك.

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


يضبط ما إذا كان يجب إزالة حقول النموذج من ملف PDF.


***Note:** The default value is 
false
.*
للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | removeFormFields | boolean | true  لإزالة حقول النموذج،  false  خلاف ذلك. |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


يتكون ملف PDF من نص، صورة، مرفق، تعليقات توضيحية، رسومات وكائنات أخرى.
قد تواجه متطلبًا لتحويل ملف PDF من مساحة ألوان RGB إلى تدرج الرمادي بحيث يكون أسرع عند طباعة تلك الملفات.
كما أن تحويل الملف إلى تدرج الرمادي يقلل أيضًا من حجم المستند، ولكن مع هذا التغيير قد تنخفض جودة المستند.
حاليًا، يتم دعم هذه الميزة عبر ميزة Pre-Flight في Adobe Acrobat.


***Note:** The default value is 
false
.*
للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Returns:**
منطقي -  true  إذا تم تحويل PDF إلى تدرج الرمادي،  false  خلاف ذلك.

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


يضبط ما إذا كان يجب تحويل ملف PDF إلى تدرج الرمادي.


***Note:** The default value is 
false
.*
للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true  لتحويل PDF إلى تدرج الرمادي،  false  خلاف ذلك. |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


كل خط يُستخدم لعرض النص على الصفحة يحتوي على مجموعة من الرموز للحروف.
مواصفات PDF تدعم \"تقسيم الخط\" أي الخط الذي يحتوي فقط على الأحرف المستخدمة.
قد يسبب هذا مشاكل عندما يجب تحديث النص (لأن الأحرف المطلوبة ربما غير موجودة في الخط)، ولكن بالنسبة للمستند الذي لا يُخطط لتغييره يسمح ذلك بتقليل الحجم.


***Note:** The default value is 
false
.*
إذا كان الملف يستخدم خطوطًا مدمجة، فهو يحتوي على جميع بيانات الخط. يمكن لـ GroupDocs.Viewer تقسيم الخطوط المدمجة لتقليل حجم الملف. للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Returns:**
منطقي -  true  إذا تم تقسيم الخطوط،  false  خلاف ذلك.

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


يضبط ما إذا كان يجب تقليل مجموعة الخطوط في ملف PDF.


***Note:** The default value is 
false
.*
إذا كان الملف يستخدم خطوطًا مدمجة، فهو يحتوي على جميع بيانات الخط. يمكن لـ GroupDocs.Viewer تقسيم الخطوط المدمجة لتقليل حجم الملف. للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | subsetFonts | boolean | true  لتقسيم الخطوط،  false  خلاف ذلك. |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وضبط جودتها.
لتمكين ضغط الصور، اضبط هذا الخيار على true. سيتم إعادة ضغط جميع الصور في المستند.
يتم تعريف الضغط بواسطة خاصية ImageQuality، التي تمثل قيمة الجودة بالنسبة المئوية.
100% تعني جودة غير متغيرة. لتقليل جودة الصورة، اضبط خاصية ImageQuality بأقل من 100.


***Note:** The default value is 
false
.*
استخدم هذا الخيار للسماح بخيارات ضغط أخرى: #setImageQuality(int).setImageQuality(int) و . للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
منطقي -  true  إذا تم ضغط الصور،  false  خلاف ذلك.

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


يضبط ما إذا كان يجب ضغط الصور في ملف PDF.


***Note:** The default value is 
false
.*
استخدم هذا الخيار للسماح بخيارات ضغط أخرى: #setImageQuality(int).setImageQuality(int) و . للحصول على مثال على الشيفرة، راجع هذه [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | compressImages | boolean | true  لضغط الصور،  false  خلاف ذلك. |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


إذا كان ملف PDF المصدر يحتوي على صور، فكر في ضغط الصور وتعيين جودتها. لتمكين ضغط الصور، اضبط خيار CompressImages إلى true. سيتم إعادة ضغط جميع الصور في المستند. يتم تعريف الضغط بواسطة الخاصية ImageQuality، التي تمثل قيمة الجودة بالنسبة المئوية. 100% تعني جودة غير متغيرة. لتقليل جودة الصورة، اضبط خيار CompressImages إلى true والخاصية ImageQuality إلى أقل من 100.

<br />


***Note:** The default value is 
100
.*
لتغيير جودة الصورة، اضبط أولاً الخاصية #setCompressImages(boolean).setCompressImages(boolean) إلى true. للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Returns:**
int - جودة الصورة (قيمة بين 1 و 100).

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


يضبط جودة الصورة لضغط الصور في ملف PDF.


***Note:** The default value is 
100
.*
لتغيير جودة الصورة، اضبط أولاً الخاصية #setCompressImages(boolean).setCompressImages(boolean) إلى true. للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageQuality | int | جودة الصورة (قيمة بين 1 و 100). |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل.
في هذه الحالة، يجب ضبط CompressImage إلى true، وResizeImages إلى true، وMaxResolution إلى القيمة المناسبة.


***Note:** The default value is 
false
.*
للسماح بهذا الخيار، اضبط الخاصية إلى true. هذا الخيار يسمح بضبط الخاصية. للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
boolean -  true  إذا تم تغيير حجم الصور،  false  وإلا.

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


يحدد ما إذا كان يجب تغيير حجم الصور في ملف PDF.


***Note:** The default value is 
false
.*
للسماح بهذا الخيار، اضبط الخاصية إلى true. هذا الخيار يسمح بضبط الخاصية. للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | resizeImages | boolean | true  لتغيير حجم الصور،  false  وإلا. |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


يمكن استخدامه مع خيار CompressImages لتغيير حجم الصور بدقة أقل. في هذه الحالة، يجب ضبط CompressImage إلى true، وResizeImages إلى true، وMaxResolution إلى القيمة المناسبة.


***Note:** The default value is 
300
.*
للسماح بهذا الخيار، اضبط الخصائص #setCompressImages(boolean).setCompressImages(boolean) و #setMaxResolution(int).setMaxResolution(int) إلى true.
للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Returns:**
int - الحد الأقصى للدقة للصور.

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


يحدد أقصى دقة لتغيير حجم الصور في ملف PDF.


***Note:** The default value is 
300
.*
للسماح بهذا الخيار، اضبط الخصائص #setCompressImages(boolean).setCompressImages(boolean) و #setMaxResolution(int).setMaxResolution(int) إلى true.
للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxResolution | int | الحد الأقصى للدقة للصور. |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


تحسين حدود خطوط وجداول Excel والخطوط للحصول على حجم ملف أصغر.


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Returns:**
boolean -  true  إذا تم تحسين جداول البيانات،  false  وإلا.

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


يحدد ما إذا كان يجب تحسين جداول البيانات في ملف PDF.


للحصول على مثال على الشفرة، راجع هذا [الوثائق](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  لتحسين جداول البيانات،  false  وإلا. |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


إزالة المعلومات الخاصة (معلومات جزء الصفحة) إذا تم تعيينها إلى true.


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  إذا تم إزالة المعلومات الخاصة،  false  وإلا.

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


يحدد ما إذا كان يجب إزالة المعلومات الخاصة من ملف PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  لإزالة المعلومات الخاصة،  false  وإلا. |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


إذا كان المستند يستخدم خطوطًا مضمنة فهذا يعني أن جميع بيانات الخطوط موضوعة في المستند.
الميزة هي أن المستند قابل للعرض بغض النظر عما إذا كان الخط مثبتًا على جهاز المستخدم\\u2019s أو لا. لكن تضمين الخطوط يجعل المستند أكبر.
طريقة إلغاء تضمين الخطوط تزيل جميع الخطوط المضمنة. هذا يقلل حجم المستند لكن قد يصبح المستند غير قابل للقراءة إذا لم يتم تثبيت الخط الصحيح.


***Note:** The default value is 
false
.*


**Returns:**
منطقي -  true  إذا تم إلغاء تضمين الخطوط،  false  غير ذلك.

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


يحدد ما إذا كان يجب فك تضمين الخطوط المضمنة في ملف PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | unembedFonts | boolean | true  لإلغاء تضمين الخطوط المضمنة،  false  غير ذلك. |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


أحيانًا يحتوي المستند على عدة تدفقات موارد متطابقة (على سبيل المثال الصور).
قد يحدث هذا على سبيل المثال عندما يتم ربط المستند بنفسه.
المستند الناتج يحتوي على نسختين مستقلتين من نفس تدفق المورد.
نحن نحلل جميع تدفقات الموارد ونقارنها. إذا تكررت التدفقات يتم دمجها، أي يبقى نسخة واحدة فقط، وتُغيّر المراجع وفقًا لذلك وتُحذف نسخ الكائن.
أحيانًا يقلل هذا من حجم المستند.


***Note:** The default value is 
false
.*


**Returns:**
منطقي -  true  إذا تم ربط التدفقات المكررة،  false  غير ذلك.

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


يحدد ما إذا كان يجب ربط التدفقات المكررة في ملف PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  لربط التدفقات المكررة،  false  غير ذلك. |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


إذا تم تعيين هذه الخاصية إلى true، سيتم إعادة استخدام محتوى الصفحة عند تحسين المستند للصفحات المتطابقة.


***Note:** The default value is 
false
.*


**Returns:**
منطقي -  true  إذا تم إعادة استخدام محتوى الصفحة،  false  غير ذلك.

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


يحدد ما إذا كان يجب السماح بإعادة استخدام محتوى الصفحة في ملف PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  للسماح بإعادة استخدام محتوى الصفحة،  false  غير ذلك. |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


أحيانًا يحتوي المستند على تدفقات موارد غير مستخدمة.
هذه التدفقات ليست \\u201cunused objects\\u201d لأنها مُشار إليها من قاموس موارد صفحة\\u2019s.
قد يحدث هذا في الحالات التي تم فيها إزالة صورة من الصفحة ولكن لم تُزال من موارد الصفحة.
أيضًا، غالبًا ما يحدث هذا عندما يتم استخراج الصفحات من المستند وتكون صفحات المستند لديها موارد \\u201ccommon\\u201d،
أي أن كائن Resources هو نفسه. يتم تحليل محتويات الصفحات لتحديد ما إذا كان تدفق المورد
مستخدمًا أم لا. يتم إزالة التدفقات غير المستخدمة. أحيانًا يقلل هذا من حجم المستند.


***Note:** The default value is 
false
.*


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
|  | removeUnusedStreams | boolean | true  لإزالة التدفقات غير المستخدمة،  false  غير ذلك. |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


أحيانًا يحتوي مستند PDF على كائنات PDF غير مُشار إليها
من أي كائن آخر في المستند. قد يحدث هذا، على سبيل المثال،
عند إزالة صفحة من شجرة صفحات المستند ولكن كائن الصفحة نفسه isn\\u2019t removed.
إزالة هذه الكائنات لا تجعل المستند غير صالح بل تقلّصه.


***Note:** The default value is 
false
.*


**Returns:**
منطقي -  true  إذا تم إزالة الكائنات غير المستخدمة،  false  غير ذلك.

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


يحدد ما إذا كان يجب إزالة الكائنات غير المستخدمة من ملف PDF.


***Note:** The default value is 
false
.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  لإزالة الكائنات غير المستخدمة،  false  غير ذلك. |
|

