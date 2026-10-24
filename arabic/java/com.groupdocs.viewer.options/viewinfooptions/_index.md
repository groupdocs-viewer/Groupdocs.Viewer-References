---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات تُستخدم لاسترجاع معلومات حول العرض."
type: docs
weight: 34
url: /ar/java/com.groupdocs.viewer.options/viewinfooptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class ViewInfoOptions extends BaseViewOptions implements IMaxSizeOptions
```

يوفر خيارات تُستخدم لاسترجاع معلومات حول العرض.


فئة ViewInfoOptions تُجَمِّع إعدادات ومعلمات إضافية التي
يمكن استخدامها لاسترجاع معلومات حول عرض في مكوّن GroupDocs.Viewer.


مثال على الاستخدام:

````

 ViewInfoOptions viewInfoOptions = ViewInfoOptions.forPngView(false);
 try (Viewer viewer = new Viewer("document.pdf")) {
     ViewInfo viewInfo = viewer.getViewInfo(viewInfoOptions);
     // Use the viewInfo object for further operations
 }
 
````


***Note:** The ViewInfoOptions class implements the IMaxSizeOptions interface to provide additional settings and size constraints for view information retrieval.*

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isExtractText()](#isExtractText--) | يشير إلى ما إذا كان استخراج النص مفعَّلًا. |
|
|  | [setExtractText(boolean extractText)](#setExtractText-boolean-) | يضبط العلامة التي تشير إلى ما إذا كان استخراج النص مفعلاً. |
|
|  | [getMaxWidth()](#getMaxWidth--) | يعيد الحد الأقصى لعرض الصورة الناتجة عند التحويل إلى PNG/JPG. |
|
|  | [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | يضبط الحد الأقصى لعرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [getMaxHeight()](#getMaxHeight--) | يعيد الحد الأقصى لارتفاع الصورة الناتجة عند التحويل إلى PNG/JPG. |
|
|  | [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | يضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [getWidth()](#getWidth--) | عرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [setWidth(int width)](#setWidth-int-) | عرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [getHeight()](#getHeight--) | ارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [setHeight(int height)](#setHeight-int-) | ارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط). |
|
|  | [forHtmlView()](#forHtmlView--) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى HTML.
|
|  | [forHtmlView(boolean renderSinglePage)](#forHtmlView-boolean-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى HTML.
|
|  | [forJpgView()](#forJpgView--) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى JPG.
|
|  | [forJpgView(boolean extractText)](#forJpgView-boolean-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى JPG.
|
|  | [forPngView()](#forPngView--) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى PNG.
|
|  | [forPngView(boolean extractText)](#forPngView-boolean-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى PNG.
|
|  | [forPdfView()](#forPdfView--) | ينشئ مثيلاً جديداً من فئة ViewInfoOptions لاسترجاع معلومات حول العرض عند التحويل إلى PDF. |
|
|  | [fromHtmlViewOptions(HtmlViewOptions options)](#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة تستند إلى كائن [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).
|
|  | [fromPngViewOptions(PngViewOptions options)](#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة تستند إلى كائن [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).
|
|  | [fromJpgViewOptions(JpgViewOptions options)](#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-) | ينشئ مثلاً جديداً من |
ViewInfoOptions
فئة تستند إلى كائن [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).
|
|  | [fromPdfViewOptions(PdfViewOptions options)](#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-) | ينشئ مثيلاً جديداً من فئة [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) استناداً إلى كائن PdfViewOptions. |
|
### isExtractText() {#isExtractText--}
```
public boolean isExtractText()
```


يشير إلى ما إذا كان استخراج النص مفعَّلًا.
استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة. للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Returns:**
boolean - True إذا كان استخراج النص مفعلاً، false وإلا.

### setExtractText(boolean extractText) {#setExtractText-boolean-}
```
public void setExtractText(boolean extractText)
```


يضبط العلامة التي تشير إلى ما إذا كان استخراج النص مفعلاً.
استخدم هذه الخاصية للحصول على النص الموجود في المستند المصدر وإحداثياته. ثم يمكنك استخدام هذه البيانات لإضافة نص قابل للتحديد فوق الصورة أو لتنفيذ بحث نصي في العرض القائم على الصورة. للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-get-text-coordinates/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | extractText | boolean | True لتمكين استخراج النص، false لتعطيله. |
|

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


يعيد الحد الأقصى لعرض الصورة الناتجة عند التحويل إلى PNG/JPG.
استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لعرض صورة الإخراج.

### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


يضبط الحد الأقصى لعرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين الحد الأقصى لعرض الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxWidth | int | الحد الأقصى لعرض صورة الإخراج. |
|

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


يعيد الحد الأقصى لارتفاع الصورة الناتجة عند التحويل إلى PNG/JPG.
استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Returns:**
int - الحد الأقصى لارتفاع صورة الإخراج.

### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


يضبط الحد الأقصى لارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين الحد الأقصى لارتفاع الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-png-jpg/). إذا قمت بتعيين الخاصية، سيتم تجاهل هذه الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | maxHeight | int | الحد الأقصى لارتفاع صورة الإخراج. |
|

### getWidth() {#getWidth--}
```
public int getWidth()
```


عرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Returns:**
int - عرض الصورة.

### setWidth(int width) {#setWidth-int-}
```
public void setWidth(int width)
```


عرض الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين عرض الصورة الناتجة (بالبيكسل). للحصول على مثال شفرة، راجع [documentation](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). إذا قمت بتعيين هذه الخاصية، سيتم تجاهل الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | width | int | عرض الصورة. |
|

### getHeight() {#getHeight--}
```
public int getHeight()
```


ارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). إذا قمت بتعيين هذه الخاصية، فسيتم تجاهل الخاصية.


**Returns:**
int - ارتفاع الصورة.

### setHeight(int height) {#setHeight-int-}
```
public void setHeight(int height)
```


ارتفاع الصورة الناتجة (بالبيكسل، للتحويل إلى PNG/JPG فقط).
استخدم هذه الخاصية لتعيين ارتفاع الصورة الناتجة (بالبكسل). للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/image-viewer-adjust-image-size/). إذا قمت بتعيين هذه الخاصية، فسيتم تجاهل الخاصية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | ارتفاع | int | ارتفاع الصورة. |
|

### forHtmlView() {#forHtmlView--}
```
public static ViewInfoOptions forHtmlView()
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى HTML.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of the  ViewInfoOptions  class.

### forHtmlView(boolean renderSinglePage) {#forHtmlView-boolean-}
```
public static ViewInfoOptions forHtmlView(boolean renderSinglePage)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى HTML.


***Note:** By default, HTML content will be rendered on multiple pages.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderSinglePage | boolean | يُمكّن محتوى HTML من العرض في صفحة واحدة. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView() {#forJpgView--}
```
public static ViewInfoOptions forJpgView()
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى JPG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forJpgView(boolean extractText) {#forJpgView-boolean-}
```
public static ViewInfoOptions forJpgView(boolean extractText)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى JPG.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | extractText | boolean | يُمكّن استخراج النص. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView() {#forPngView--}
```
public static ViewInfoOptions forPngView()
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى PNG.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPngView(boolean extractText) {#forPngView-boolean-}
```
public static ViewInfoOptions forPngView(boolean extractText)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة لاسترجاع معلومات حول العرض عند التحويل إلى PNG.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | extractText | boolean | يُمكّن استخراج النص. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### forPdfView() {#forPdfView--}
```
public static ViewInfoOptions forPdfView()
```


ينشئ مثيلاً جديداً من فئة ViewInfoOptions لاسترجاع معلومات حول العرض عند التحويل إلى PDF.


**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) class.

### fromHtmlViewOptions(HtmlViewOptions options) {#fromHtmlViewOptions-com.groupdocs.viewer.options.HtmlViewOptions-}
```
public static ViewInfoOptions fromHtmlViewOptions(HtmlViewOptions options)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة تستند إلى كائن [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) | خيارات عرض HTML. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPngViewOptions(PngViewOptions options) {#fromPngViewOptions-com.groupdocs.viewer.options.PngViewOptions-}
```
public static ViewInfoOptions fromPngViewOptions(PngViewOptions options)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة تستند إلى كائن [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) | خيارات عرض PNG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromJpgViewOptions(JpgViewOptions options) {#fromJpgViewOptions-com.groupdocs.viewer.options.JpgViewOptions-}
```
public static ViewInfoOptions fromJpgViewOptions(JpgViewOptions options)
```


ينشئ مثلاً جديداً من
ViewInfoOptions
فئة تستند إلى كائن [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [JpgViewOptions](../../com.groupdocs.viewer.options/jpgviewoptions) | خيارات عرض JPG. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - New instance of  ViewInfoOptions  class.

### fromPdfViewOptions(PdfViewOptions options) {#fromPdfViewOptions-com.groupdocs.viewer.options.PdfViewOptions-}
```
public static ViewInfoOptions fromPdfViewOptions(PdfViewOptions options)
```


ينشئ مثيلاً جديداً من فئة [ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) استناداً إلى كائن PdfViewOptions.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | options | [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions) | خيارات عرض PDF. |
|

**Returns:**
[ViewInfoOptions](../../com.groupdocs.viewer.options/viewinfooptions) - A new instance of the ViewInfoOptions class.

