---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير المستندات إلى تنسيق PNG."
type: docs
weight: 25
url: /ar/java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

يوفر خيارات لتصيير المستندات إلى تنسيق PNG.


تحتوي فئة PngViewOptions على إعدادات ومعلمات إضافية يمكن استخدامها
للتحكم في تحويل المستندات إلى صيغة PNG في مكوّن GroupDocs.Viewer.


مثال على الاستخدام:

````

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.*
للتفاصيل، راجع هذه [page](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/) وأقسامها الفرعية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | ينشئ مثلاً جديداً من |
PngViewOptions
الفئة.
|
|  | [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | ينشئ مثلاً جديداً من |
PngViewOptions
الفئة.
|
|  | [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | ينشئ مثلاً جديداً من |
PngViewOptions
الفئة.
|
|  | [PngViewOptions()](#PngViewOptions--) | يُنشئ نسخة جديدة من |
PngViewOptions
الفئة.
|
|  | [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | ينشئ مثلاً جديداً من |
PngViewOptions
الفئة.
|
|  | [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | ينشئ مثلاً جديداً من |
PngViewOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getMaxWidth()](#getMaxWidth--) | يعيد الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | يضبط الحد الأقصى لعرض صورة الإخراج بالبكسل. |
|
|  | [getMaxHeight()](#getMaxHeight--) | يرجع الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | يضبط الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
|
|  | [isExtractText()](#isExtractText--) | يحدد ما إذا كان استخراج النص مفعلاً. |
|
|  | [setExtractText(boolean value)](#setExtractText-boolean-) | يفعل أو يعطل استخراج النص. |
|
|  | [getWidth()](#getWidth--) | يرجع عرض الصورة الناتجة بالبكسل. |
|
|  | [setWidth(int value)](#setWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
|
|  | [getHeight()](#getHeight--) | يرجع ارتفاع الصورة الناتجة بالبكسل. |
|
|  | [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع الصورة الناتجة بالبكسل. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يسترجع رد النداء لتقدير تقدم حفظ المستند. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط رد النداء لتقدير تقدم حفظ المستند. |
|
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


ينشئ مثلاً جديداً من
PngViewOptions
الفئة.


للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
|

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


ينشئ مثلاً جديداً من
PngViewOptions
الفئة.


للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | الطريقة التي تُحرّر الدفق الذي أنشأته الطريقة المعينة للمعامل createPageStream. |
|

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


ينشئ مثلاً جديداً من
PngViewOptions
الفئة.


للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء وإطلاق تدفق الصفحة الناتجة. |
|

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


يُنشئ نسخة جديدة من
PngViewOptions
الفئة.


يقوم هذا المُنشئ بتهيئة نسخة جديدة من
PngViewOptions

مع \"p_{0}.png\" كتنسيق مسار الملف لملفات الإخراج.
ستُوضع ملفات الإخراج في دليل العمل الحالي للتطبيق.
للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


ينشئ مثلاً جديداً من
PngViewOptions
الفئة.


على سبيل المثال، إذا كان تنسيق مسار الملف هو 'page_{0}.png'، فإن ملفات الإخراج ستكون
مُسماة كـ 'page_1.png'، 'page_2.png'، وهكذا، بناءً على رقم الصفحة.


***Note:** It is important to note that the output files will be placed into the current working directory of the application.*
للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | تنسيق مسار الملف، مثال: 'page_{0}.png'. |
|

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


ينشئ مثلاً جديداً من
PngViewOptions
الفئة.


على سبيل المثال، إذا كان تنسيق مسار الملف هو 'page_{0}.png'، فإن ملفات الإخراج ستكون
مُسماة كـ 'page_1.png'، 'page_2.png'، وهكذا، بناءً على رقم الصفحة.
للحصول على مثال الكود، راجع هذه [documentation](../https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | تنسيق مسار الملف، مثال: 'page_{0}.png'. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


يعيد الحد الأقصى لعرض الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين الحد الأقصى لعرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لعرض صورة الإخراج.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


يضبط الحد الأقصى لعرض صورة الإخراج بالبكسل.


استخدم هذه الخاصية لتعيين الحد الأقصى لعرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxWidth | int | الحد الأقصى لعرض صورة الإخراج. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


يرجع الحد الأقصى لارتفاع الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لارتفاع صورة الإخراج.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


يضبط الحد الأقصى لارتفاع صورة الإخراج بالبكسل.


استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxHeight | int | الحد الأقصى لارتفاع صورة الإخراج. |
|

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


يحدد ما إذا كان استخراج النص مفعلاً.


قد يكون هذا الخيار مفيدًا عندما تريد إضافة طبقة نص قابلة للتحديد فوق الصورة.
استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة.
للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/).


**Returns:**
boolean -  true  إذا تم تمكين استخراج النص،  false  خلاف ذلك.

### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


يفعل أو يعطل استخراج النص.


قد يكون هذا الخيار مفيدًا عندما تريد إضافة طبقة نص قابلة للتحديد فوق الصورة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين استخراج النص،  false  لتعطيله. |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يرجع عرض الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين عرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Returns:**
int - عرض صورة الإخراج.

### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين عرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | عرض صورة الإخراج. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يرجع ارتفاع الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين ارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Returns:**
int - ارتفاع صورة الإخراج.

### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع الصورة الناتجة بالبكسل.


استخدم هذه الخاصية لتعيين ارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | int | ارتفاع صورة الإخراج. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يسترجع رد النداء لتقدير تقدم حفظ المستند.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد النداء لتقدير تقدم حفظ المستند.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط رد النداء لتقدير تقدم حفظ المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد النداء لتقدير تقدم حفظ المستند. |
|

