---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض المستندات بصيغة PDF."
type: docs
weight: 23
url: /ar/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

يوفر خيارات لعرض المستندات بصيغة PDF.

تحتوي فئة PdfViewOptions على إعدادات ومعلمات إضافية يمكن استخدامها للتحكم في تحويل المستندات إلى صيغة PDF في مكوّن GroupDocs.Viewer. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | ينشئ نسخة جديدة من فئة  PdfViewOptions . |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | ينشئ نسخة جديدة من فئة  PdfViewOptions . |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | ينشئ نسخة جديدة من فئة  PdfViewOptions . |
| [PdfViewOptions()](#PdfViewOptions--) | ينشئ نسخة جديدة من فئة  PdfViewOptions  بإعدادات افتراضية. |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | ينشئ نسخة جديدة من فئة  PdfViewOptions . |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | ينشئ نسخة جديدة من فئة  PdfViewOptions . |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مع خيارات مختلفة. |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مع خيارات مختلفة. |
| [getImageMaxWidth()](#getImageMaxWidth--) | يسترجع الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
| [getImageMaxHeight()](#getImageMaxHeight--) | يسترجع الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
| [getImageWidth()](#getImageWidth--) | يسترجع عرض الصورة الناتجة بالبكسل. |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
| [getImageHeight()](#getImageHeight--) | يسترجع ارتفاع الصورة الناتجة بوحدات البكسل. |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | يضبط ارتفاع الصورة الناتجة بوحدات البكسل. |
| [getSecurity()](#getSecurity--) | يسترجع خيارات الأمان لمستند PDF الناتج. |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | يضبط خيارات الأمان لمستند PDF الناتج. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يسترجع رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email. |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


ينشئ نسخة جديدة من فئة  PdfViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


ينشئ نسخة جديدة من فئة  PdfViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | الطريقة المستخدمة لإنشاء الدفق لكتابة بيانات ملف الإخراج. |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | الطريقة المستخدمة لإطلاق الدفق الذي أنشأته طريقة createFileStream. |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


ينشئ نسخة جديدة من فئة  PdfViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | المصنع الذي ينفذ طرقًا لإنشاء وإطلاق دفق ملف الإخراج. |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


ينشئ نسخة جديدة من فئة  PdfViewOptions  بإعدادات افتراضية.

هذا المُنشئ ينشئ كائن  PdfViewOptions  جديد مع "output.pdf" كتنسيق مسار الملف للملف الناتج. سيتم وضع الملف الناتج في دليل العمل الحالي للتطبيق. للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


ينشئ نسخة جديدة من فئة  PdfViewOptions .

هذا المُنشئ ينشئ كائن  PdfViewOptions  جديد مع المعامل  outputFilePath  المحدد الذي يمثل مسار ملف PDF الناتج. للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| outputFilePath | java.lang.String | مسار ملف PDF الناتج. |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


ينشئ نسخة جديدة من فئة  PdfViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | مسار ملف PDF الناتج. |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مع خيارات مختلفة.

هذا الخيار مدعوم لأي صيغ ملفات إدخال مدعومة للتحويل إلى PDF: [Supported document formats][] للتفاصيل وعينات الكود، انظر هذه [page][] وأقسامها.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


قلل حجم ملف PDF الناتج باستخدام تقنيات تحسين مع خيارات مختلفة.

هذا الخيار مدعوم لأي صيغ ملفات إدخال مدعومة للتحويل إلى PDF: [Supported document formats][] للتفاصيل وعينات الكود، انظر هذه [page][] وأقسامها.


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | كائن PdfOptimizationOptions أو null. |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


يسترجع الحد الأقصى لعرض الصورة الناتجة بوحدات البكسل. هذا المعامل يُطبق فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لضبط الحد الأقصى لعرض الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى PDF. للتفاصيل، انظر [documentation][]. إذا قمت بضبط الخاصية، سيتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - الحد الأقصى لعرض الصورة الناتجة بوحدات البكسل.
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة بوحدات البكسل. هذا المعامل يُطبق فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لضبط الحد الأقصى لعرض الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى PDF. للتفاصيل، انظر [documentation][]. إذا قمت بضبط الخاصية، سيتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageMaxWidth | int | الحد الأقصى لعرض الصورة الناتجة بوحدات البكسل. |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


يسترجع الحد الأقصى لارتفاع الصورة الناتجة بوحدات البكسل. هذا المعامل يُطبق فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لضبط الحد الأقصى لارتفاع الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند تحويل صورة واحدة إلى PDF. للتفاصيل، انظر [documentation][]. إذا قمت بضبط الخاصية، سيتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - الحد الأقصى لارتفاع الصورة الناتجة بوحدات البكسل.
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


يحدد الحد الأقصى لارتفاع الصورة الناتجة بوحدات البكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند عرض صورة واحدة إلى HTML فقط. للحصول على التفاصيل، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageMaxHeight | int | الارتفاع الأقصى للصورة الناتجة بوحدات البكسل. |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


يسترجع عرض الصورة الناتجة بوحدات البكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند عرض صورة واحدة إلى PDF. للحصول على التفاصيل، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - عرض الصورة الناتجة بوحدات البكسل.
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


يحدد عرض الصورة الناتجة بوحدات البكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى PDF.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageWidth | int | عرض الصورة الناتجة بوحدات البكسل. |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


يسترجع ارتفاع الصورة الناتجة بوحدات البكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند عرض صورة واحدة إلى HTML فقط. للحصول على التفاصيل، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - ارتفاع الصورة الناتجة بوحدات البكسل.
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


يحدد ارتفاع الصورة الناتجة بوحدات البكسل. ينطبق هذا المعامل فقط عند تحويل صورة واحدة إلى HTML.

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بوحدات البكسل). يقوم GroupDocs.Viewer بتطبيق هذه الخاصية عند عرض صورة واحدة إلى HTML فقط. للحصول على التفاصيل، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| imageHeight | int | ارتفاع الصورة الناتجة بوحدات البكسل. |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


يسترجع خيارات الأمان لمستند PDF الناتج.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


يضبط خيارات الأمان لمستند PDF الناتج.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | خيارات الأمان لمستند PDF الناتج. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يسترجع رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد الاتصال لتقدير تقدم حفظ المستند.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط رد النداء المستخدم لتقدير تقدم حفظ مستند Words أو Email.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد الاتصال لتقدير تقدم حفظ المستند. |

