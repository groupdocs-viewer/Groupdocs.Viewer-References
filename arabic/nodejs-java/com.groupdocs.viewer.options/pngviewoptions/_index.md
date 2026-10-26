---
title: "PngViewOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض المستندات بصيغة PNG."
type: docs
weight: 25
url: /ar/nodejs-java/com.groupdocs.viewer.options/pngviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class PngViewOptions extends ViewOptions implements IMaxSizeOptions
```

يوفر خيارات لعرض المستندات بصيغة PNG.

تُجَمِّع فئة PngViewOptions إعدادات ومعلمات إضافية يمكن استخدامها للتحكم في تحويل المستندات إلى صيغة PNG في مكوّن GroupDocs.Viewer.

مثال على الاستخدام:

```

 PngViewOptions options = new PngViewOptions();
 options.setHeight(1080);
 options.setWidth(1920);
 options.setRenderComments(true);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The PngViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output PNG images.* For details, see this [page][] and its children.


[page]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PngViewOptions(CreatePageStream createPageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions . |
| [PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions . |
| [PngViewOptions(PageStreamFactory pageStreamFactory)](#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions . |
| [PngViewOptions()](#PngViewOptions--) | يُنشئ مثيلًا جديدًا من فئة  PngViewOptions . |
| [PngViewOptions(String filePathFormat)](#PngViewOptions-java.lang.String-) | يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions . |
| [PngViewOptions(Path filePathFormat)](#PngViewOptions-java.nio.file.Path-) | يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions . |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | يعيد الحد الأقصى لعرض صورة الإخراج بالبكسل. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
| [getMaxHeight()](#getMaxHeight--) | يرجع الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
| [isExtractText()](#isExtractText--) | يحدد ما إذا كان استخراج النص مفعَّلًا. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | يفعّل أو يعطّل استخراج النص. |
| [getWidth()](#getWidth--) | يرجع عرض صورة الإخراج بالبكسل. |
| [setWidth(int value)](#setWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
| [getHeight()](#getHeight--) | يرجع ارتفاع صورة الإخراج بالبكسل. |
| [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع الصورة الناتجة بوحدات البكسل. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يسترجع رد النداء لتقدير تقدم حفظ المستند. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط رد النداء لتقدير تقدم حفظ المستند. |
### PngViewOptions(CreatePageStream createPageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream)
```


يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |

### PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#PngViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public PngViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | الطريقة التي تُفرج عن الدفق الذي تم إنشاؤه بواسطة الطريقة المعينة للمعامل createPageStream. |

### PngViewOptions(PageStreamFactory pageStreamFactory) {#PngViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public PngViewOptions(PageStreamFactory pageStreamFactory)
```


يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |

### PngViewOptions() {#PngViewOptions--}
```
public PngViewOptions()
```


يُنشئ مثيلًا جديدًا من فئة  PngViewOptions .

هذا المُنشئ يهيئ نسخة جديدة من PngViewOptions باستخدام "p\_\{0\}.png" كتنسيق مسار الملف للملفات الناتجة. سيتم وضع الملفات الناتجة في دليل العمل الحالي للتطبيق. للحصول على مثال الكود، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

### PngViewOptions(String filePathFormat) {#PngViewOptions-java.lang.String-}
```
public PngViewOptions(String filePathFormat)
```


يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions .

على سبيل المثال، إذا كان تنسيق مسار الملف هو 'page\_\{0\}.png'، فستُسمى الملفات الناتجة كـ 'page\_1.png'، 'page\_2.png'، وهكذا وفقًا لرقم الصفحة.

***Note:** It is important to note that the output files will be placed into the current working directory of the application.* For the code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف، مثال: 'page\_\{0\}.png'. |

### PngViewOptions(Path filePathFormat) {#PngViewOptions-java.nio.file.Path-}
```
public PngViewOptions(Path filePathFormat)
```


يُنشئ مثيلًا جديدًا من الفئة  PngViewOptions .

على سبيل المثال، إذا كان تنسيق مسار الملف هو 'page\_\{0\}.png'، فستُسمى الملفات الناتجة كـ 'page\_1.png'، 'page\_2.png'، وهكذا وفقًا لرقم الصفحة. للحصول على مثال الكود، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-png

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | تنسيق مسار الملف، مثال: 'page\_\{0\}.png'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


يعيد الحد الأقصى لعرض صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لعرض الصورة الناتجة.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxWidth | int | الحد الأقصى لعرض الصورة الناتجة. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


يرجع الحد الأقصى لارتفاع صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لارتفاع الصورة الناتجة.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxHeight | int | الحد الأقصى لارتفاع الصورة الناتجة. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


يحدد ما إذا كان استخراج النص مفعَّلًا.

قد يكون هذا الخيار مفيدًا عندما تريد إضافة طبقة نص قابلة للتحديد فوق الصورة. استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة. للحصول على مثال الكود، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  إذا تم تمكين استخراج النص،  false  خلاف ذلك.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


يفعّل أو يعطّل استخراج النص.

قد يكون هذا الخيار مفيدًا عندما تريد إضافة طبقة نص قابلة للتحديد فوق الصورة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين استخراج النص،  false  لتعطيله. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يرجع عرض صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - عرض صورة الإخراج.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عرض صورة الإخراج. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يرجع ارتفاع صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - ارتفاع الصورة الناتجة.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع الصورة الناتجة بوحدات البكسل.

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | ارتفاع الصورة الناتجة. |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يسترجع رد النداء لتقدير تقدم حفظ المستند.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد الاتصال لتقدير تقدم حفظ المستند.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط رد النداء لتقدير تقدم حفظ المستند.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد الاتصال لتقدير تقدم حفظ المستند. |

