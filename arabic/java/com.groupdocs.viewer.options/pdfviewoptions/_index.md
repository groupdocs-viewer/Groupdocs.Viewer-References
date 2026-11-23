---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير المستندات إلى تنسيق PDF."
type: docs
weight: 23
url: /ar/java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

يوفر خيارات لتصيير المستندات إلى تنسيق PDF.


تُجَمِّع فئة PdfViewOptions إعدادات ومعلمات إضافية
التي يمكن استخدامها للتحكم في تحويل المستندات إلى تنسيق PDF في مكوّن GroupDocs.Viewer.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


مثال على الاستخدام:

````

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | ينشئ مثلاً جديداً من |
PdfViewOptions
الفئة.
|
|  | [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | ينشئ مثلاً جديداً من |
PdfViewOptions
الفئة.
|
|  | [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | ينشئ مثيلًا جديدًا لفئة  PdfViewOptions . |
|
|  | [PdfViewOptions()](#PdfViewOptions--) | ينشئ مثيلًا جديدًا لفئة  PdfViewOptions  مع الإعدادات الافتراضية. |
|
|  | [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | ينشئ مثلاً جديداً من |
PdfViewOptions
الفئة.
|
|  | [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | ينشئ مثلاً جديداً من |
PdfViewOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مختلفة مع خيارات متعددة. |
|
|  | [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مختلفة مع خيارات متعددة. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | يسترجع الحد الأقصى لعرض صورة الإخراج بالبكسل. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | يضبط الحد الأقصى لعرض صورة الإخراج بالبكسل. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | يسترجع الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | يضبط الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
|
|  | [getImageWidth()](#getImageWidth--) | يسترجع عرض صورة الإخراج بالبكسل. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
|
|  | [getImageHeight()](#getImageHeight--) | يسترجع ارتفاع الصورة الناتجة بالبكسل. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | يضبط ارتفاع الصورة الناتجة بالبكسل. |
|
|  | [getSecurity()](#getSecurity--) | يسترجع خيارات الأمان لمستند PDF الناتج. |
|
|  | [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | يضبط خيارات الأمان لمستند PDF الناتج. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يسترجع رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email. |
|
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


ينشئ مثلاً جديداً من
PdfViewOptions
الفئة.


للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


ينشئ مثلاً جديداً من
PdfViewOptions
الفئة.


للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | الطريقة المستخدمة لإنشاء الدفق لكتابة بيانات ملف الإخراج. |
|
|  | releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | الطريقة المستخدمة لإطلاق الدفق الذي أنشأته طريقة  createFileStream . |
|

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


ينشئ مثيلًا جديدًا لفئة  PdfViewOptions .


للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | المصنع الذي ينفّذ طرقًا لإنشاء وإطلاق دفق ملف الإخراج. |
|

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


ينشئ مثيلًا جديدًا لفئة  PdfViewOptions  مع الإعدادات الافتراضية.


هذا المُنشئ ينشئ جديدًا
PdfViewOptions
كائن مع "output.pdf" كصيغة مسار الملف للملف الناتج.
سيتم وضع ملف الإخراج في دليل العمل الحالي للتطبيق.
للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


ينشئ مثلاً جديداً من
PdfViewOptions
الفئة.


هذا المُنشئ ينشئ جديدًا
PdfViewOptions
كائن مع المحدد
outputFilePath
معامل
يمثل المسار لملف PDF الناتج.
للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFilePath | java.lang.String | المسار لملف PDF الناتج. |
|

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


ينشئ مثلاً جديداً من
PdfViewOptions
الفئة.


للحصول على مثال الكود، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | outputFilePath | java.nio.file.Path | المسار لملف PDF الناتج. |
|

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مختلفة مع خيارات متعددة.


هذا الخيار مدعوم لأي صيغ ملفات إدخال مدعومة للتحويل إلى PDF: [صيغ المستندات المدعومة](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
للتفاصيل وعينات الكود، راجع هذه [الصفحة](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) وأقسامها الفرعية.


**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.

### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مختلفة مع خيارات متعددة.


هذا الخيار مدعوم لأي صيغ ملفات إدخال مدعومة للتحويل إلى PDF: [صيغ المستندات المدعومة](../https://docs.groupdocs.com/viewer/net/supported-document-formats/)
للتفاصيل وعينات الكود، راجع هذه [الصفحة](../https://docs.groupdocs.com/viewer/net/optimization-pdf-options/) وأقسامها الفرعية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | كائن PdfOptimizationOptions أو null. |
|

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


يسترجع الحد الأقصى لعرض الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). يطبق GroupDocs.Viewer هذه الخاصية عند تصيير صورة واحدة إلى PDF. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لعرض الصورة الناتجة بالبكسل.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). يطبق GroupDocs.Viewer هذه الخاصية عند تصيير صورة واحدة إلى PDF. للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageMaxWidth | int | الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


يسترجع الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى PDF. للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لارتفاع الصورة الناتجة بالبكسل.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى HTML فقط. للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageMaxHeight | int | الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


يسترجع عرض الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لضبط عرض الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى PDF. للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Returns:**
int - عرض الصورة الناتجة بالبكسل.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


يضبط عرض الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى PDF.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageWidth | int | عرض الصورة الناتجة بالبكسل. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


يسترجع ارتفاع الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لضبط ارتفاع الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى HTML فقط. للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Returns:**
int - ارتفاع الصورة الناتجة بالبكسل.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


يضبط ارتفاع الصورة الناتجة بالبكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.


استخدم هذه الخاصية لضبط ارتفاع الصورة الناتجة (بالبكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى HTML فقط. للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/).
إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageHeight | int | ارتفاع الصورة الناتجة بالبكسل. |
|

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


يسترجع خيارات الأمان لمستند PDF الناتج.


للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.

### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


يضبط خيارات الأمان لمستند PDF الناتج.


للحصول على تفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/protect-pdf-documents/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Security](../../com.groupdocs.viewer.options/security) | خيارات الأمان لمستند PDF الناتج. |
|

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يسترجع رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد النداء لتقدير تقدم حفظ المستند.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد النداء لتقدير تقدم حفظ المستند. |
|

