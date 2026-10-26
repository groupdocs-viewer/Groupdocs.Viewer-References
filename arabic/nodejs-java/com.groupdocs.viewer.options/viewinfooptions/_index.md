---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات تُستخدم لاسترجاع معلومات حول العرض."
type: docs
weight: 34
url: /ar/nodejs-java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object، [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

يوفر خيارات تُستخدم لاسترجاع معلومات حول العرض.

تحتوي فئة ViewInfoOptions على إعدادات ومعلمات إضافية يمكن استخدامها لاسترداد معلومات حول عرض في مكوّن GroupDocs.Viewer.

مثال على الاستخدام:

```

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
```

***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isExtractText()](#isExtractText--) | يشير إلى ما إذا كان استخراج النص مفعلاً. |
| [setExtractText(boolean extractText)](#setExtractText-boolean-) | يضبط العلامة التي تشير إلى ما إذا كان استخراج النص مفعلاً. |
| [getMaxWidth()](#getMaxWidth--) | يرجع الحد الأقصى لعرض الصورة الناتجة عند العرض إلى PNG/JPG. |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | يضبط الحد الأقصى لعرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [getMaxHeight()](#getMaxHeight--) | يرجع الحد الأقصى لارتفاع الصورة الناتجة عند العرض إلى PNG/JPG. |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | يضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [getWidth()](#getWidth--) | عرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [setWidth(int width)](#setWidth-int-) | عرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [getHeight()](#getHeight--) | ارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [setHeight(int height)](#setHeight-int-) | ارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط). |
| [forHtmlView()](#forHtmlView--) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى HTML. |
| [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى HTML. |
| [forJpgView()](#forJpgView--) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى JPG. |
| [forJpgView(boolean extractText)](#forJpgView-boolean-) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى JPG. |
| [forPngView()](#forPngView--) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى PNG. |
| [forPngView(boolean extractText)](#forPngView-boolean-) | ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى PNG. |
| [forPdfView()](#forPdfView--) | يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions لاسترداد معلومات العرض عند التحويل إلى PDF. |
| [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions). |
| [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions). |
| [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions). |
| [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | يقوم بإنشاء نسخة جديدة من الفئة [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) بناءً على كائن PdfViewOptions. |
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


يشير إلى ما إذا كان استخراج النص مفعلاً.

استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة. للحصول على مثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Returns:**
منطقي - True إذا تم تمكين استخراج النص، false خلاف ذلك.
### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


يضبط العلامة التي تشير إلى ما إذا كان استخراج النص مفعلاً.

استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة. للحصول على مثال على الشيفرة، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| extractText | boolean | True لتمكين استخراج النص، false لتعطيله. |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


يرجع الحد الأقصى لعرض الصورة الناتجة عند العرض إلى PNG/JPG.

استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لعرض الصورة الناتجة.
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxWidth | int | الحد الأقصى لعرض الصورة الناتجة. |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


يرجع الحد الأقصى لارتفاع الصورة الناتجة عند العرض إلى PNG/JPG.

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - الحد الأقصى لارتفاع الصورة الناتجة.
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


يضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين الخاصية  ، يتم تجاهل هذه الخاصية.


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| maxHeight | int | الحد الأقصى لارتفاع الصورة الناتجة. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


عرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
عدد صحيح - عرض الصورة.
### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


عرض الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


ارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Returns:**
عدد صحيح - ارتفاع الصورة.
### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


ارتفاع الصورة الناتجة (بالبكسل، للعرض إلى PNG/JPG فقط).

استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال الكود، راجع [documentation][]. إذا قمت بتعيين هذه الخاصية، يتم تجاهل الخاصية  .


[documentation]: https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| height | int | ارتفاع الصورة. |

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى HTML.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.
### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى HTML.

***Note:** By default, HTML content will be rendered on multiple pages.*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderSinglePage | boolean | يُمكّن محتوى HTML من العرض في صفحة واحدة. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى JPG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى JPG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| extractText | boolean | يُمكّن استخراج النص. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى PNG.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


ينشئ مثيلاً جديدًا من فئة  ViewInfoOptions  لاسترداد معلومات حول العرض عند العرض إلى PNG.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| extractText | boolean | يُمكّن استخراج النص. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions لاسترداد معلومات العرض عند التحويل إلى PDF.

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.
### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | خيارات عرض HTML. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | خيارات عرض PNG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


يقوم بإنشاء نسخة جديدة من الفئة ViewInfoOptions بناءً على كائن [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | خيارات عرض JPG. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.
### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


يقوم بإنشاء نسخة جديدة من الفئة [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) بناءً على كائن PdfViewOptions.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | خيارات عرض PDF. |

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.
