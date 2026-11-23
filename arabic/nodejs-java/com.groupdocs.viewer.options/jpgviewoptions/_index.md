---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض المستندات بصيغة JPG."
type: docs
weight: 17
url: /ar/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

يوفر خيارات لعرض المستندات بصيغة JPG.

تحتوي فئة JpgViewOptions على إعدادات ومعلمات إضافية يمكن استخدامها للتحكم في تحويل المستندات إلى صيغة JPG في مكوّن GroupDocs.Viewer.

مثال على الاستخدام:

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions . |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions . |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions . |
| [JpgViewOptions()](#JpgViewOptions--) | يُنشئ مثيلًا جديدًا من  JpgViewOptions  باستخدام \"p\\_\\{0\\}.jpg\" كتنسيق مسار الملف للملفات الناتجة. |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions . |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions . |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | يحصل على الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
| [getMaxHeight()](#getMaxHeight--) | يحصل على الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
| [getQuality()](#getQuality--) | يحصل على جودة الصورة الناتجة. |
| [setQuality(byte value)](#setQuality-byte-) | يضبط جودة الصورة الناتجة. |
| [isExtractText()](#isExtractText--) | يُمكّن استخراج النص. |
| [setExtractText(boolean value)](#setExtractText-boolean-) | يفعّل أو يعطّل استخراج النص. |
| [getWidth()](#getWidth--) | يحصل على عرض صورة الإخراج بالبكسل. |
| [setWidth(int value)](#setWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الصورة الناتجة بالبكسل. |
| [setHeight(int value)](#setHeight-int-) | يضبط ارتفاع الصورة الناتجة بوحدات البكسل. |
| [getPageStreamFactory()](#getPageStreamFactory--) | يحصل على المصنع الذي ينفّذ طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يحصل على رد النداء لتقدير تقدم حفظ مستند Words أو Email. |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط رد النداء لتقدير تقدم حفظ مستند Words أو Email. |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تنشئ الدفق المستخدم لكتابة بيانات صفحة الإخراج. |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | الطريقة التي تُطلق التدفق الذي أنشأته الطريقة المعيّنة للمنفذ الممرّر إلى معامل  createPageStream . |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج. |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


يُنشئ مثيلًا جديدًا من  JpgViewOptions  باستخدام \"p\\_\\{0\\}.jpg\" كتنسيق مسار الملف للملفات الناتجة. سيتم وضع الملفات الناتجة في دليل العمل الحالي للتطبيق.

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.lang.String | تنسيق مسار الملف، مثال: 'page\\_\\{0\\}.jpg'. |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


يُنشئ مثيلًا جديدًا من فئة  JpgViewOptions .

للحصول على مثال الكود، انظر [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | تنسيق مسار الملف، مثال: 'page\\_\\{0\\}.jpg'. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


يحصل على الحد الأقصى لعرض الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتحديد الحد الأقصى لعرض الصورة الناتجة (بالبكسل). لعينة الكود، انظر إلى [documentation][]. إذا قمت بتعيين الخاصية \\#setWidth(int).setWidth(int)، سيتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لعرض صورة الإخراج.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتحديد الحد الأقصى لعرض الصورة الناتجة (بالبكسل). لعينة الكود، انظر إلى [documentation][]. إذا قمت بتعيين الخاصية \\#setWidth(int).setWidth(int)، سيتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxWidth | int | الحد الأقصى لعرض صورة الإخراج. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


يحصل على الحد الأقصى لارتفاع صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين الخاصية \#setHeight(int).setHeight(int)، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لارتفاع صورة الإخراج.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


يضبط الحد الأقصى لارتفاع الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين الخاصية \#setHeight(int).setHeight(int)، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxHeight | int | الحد الأقصى لارتفاع صورة الإخراج. |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


يحصل على جودة الصورة الناتجة.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - جودة صورة الإخراج.
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


يضبط جودة الصورة الناتجة.

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte | جودة صورة الإخراج. |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


يُمكّن استخراج النص.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  إذا تم تمكين استخراج النص،  false  خلاف ذلك.
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


يفعّل أو يعطّل استخراج النص.

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين استخراج النص،  false  لتعطيله. |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض صورة الإخراج بالبكسل.

استخدم هذه الخاصية لتعيين عرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية \#setMaxWidth(int).setMaxWidth(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - عرض صورة الإخراج.
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


يضبط عرض الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين عرض صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية \#setMaxWidth(int).setMaxWidth(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | عرض صورة الإخراج. |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع الصورة الناتجة بالبكسل.

استخدم هذه الخاصية لتعيين ارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية \#setMaxHeight(int).setMaxHeight(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - ارتفاع الصورة الناتجة.
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


يضبط ارتفاع الصورة الناتجة بوحدات البكسل.

استخدم هذه الخاصية لتعيين ارتفاع صورة الإخراج (بالبكسل). للحصول على مثال شفرة، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية \#setMaxHeight(int).setMaxHeight(int).


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | ارتفاع الصورة الناتجة. |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


يحصل على المصنع الذي ينفّذ طرقًا لإنشاء وإطلاق تدفق صفحة الإخراج.

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يحصل على رد النداء لتقدير تقدم حفظ مستند Words أو Email.

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد الاتصال لتقدير تقدم حفظ المستند.
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط رد النداء لتقدير تقدم حفظ مستند Words أو Email.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد الاتصال لتقدير تقدم حفظ المستند. |

