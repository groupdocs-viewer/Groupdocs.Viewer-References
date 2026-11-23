---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لعرض المستندات بصيغة HTML."
type: docs
weight: 16
url: /ar/java/com.groupdocs.viewer.options/htmlviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class HtmlViewOptions extends ViewOptions
```

يوفر خيارات لعرض المستندات بصيغة HTML.


فئة HtmlViewOptions تضم إعدادات ومعلمات إضافية
التي يمكن استخدامها للتحكم في عرض المستندات بصيغة HTML في مكوّن GroupDocs.Viewer.


للتفاصيل، انظر الـ[topic](../https://docs.groupdocs.com/viewer/java/rendering-to-html/) وأقسامه الفرعية.


مثال على الاستخدام:

````

 HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources();
 options.setExcludeFonts(true);
 options.setFontsToExclude(Arrays.asList("font-name"));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
````


## الحقول

| حقل | الوصف |
| --- | --- |
| [CREATE_PAGE_STREAM](#CREATE-PAGE-STREAM) |  |
| [FILE_PATH_FORMAT](#FILE-PATH-FORMAT) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isRenderResponsive()](#isRenderResponsive--) | يحدد ما إذا كان العرض المتجاوب مفعّلاً. |
|
|  | [setRenderResponsive(boolean value)](#setRenderResponsive-boolean-) | يضبط ما إذا كان العرض المتجاوب مفعّلاً. |
|
|  | [isMinify()](#isMinify--) | يتحقق مما إذا كان تقليل حجم محتوى HTML وموارد HTML مفعّلاً. |
|
|  | [setMinify(boolean value)](#setMinify-boolean-) | يضبط ما إذا كان تقليل حجم محتوى HTML وموارد HTML مفعّلاً. |
|
|  | [isRenderToSinglePage()](#isRenderToSinglePage--) | يُمكّن عرض المستند بالكامل إلى ملف HTML واحد. |
|
|  | [setRenderToSinglePage(boolean renderSinglePage)](#setRenderToSinglePage-boolean-) | يُمكّن عرض المستند بالكامل إلى ملف HTML واحد. |
|
|  | [getImageMaxWidth()](#getImageMaxWidth--) | يعيد الحد الأقصى لعرض الصورة الناتجة بالبكسل. |
|
|  | [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | يضبط الحد الأقصى لعرض صورة الإخراج بالبكسل. |
|
|  | [getImageMaxHeight()](#getImageMaxHeight--) | يحصل على الحد الأقصى لارتفاع الصورة الناتجة بالبكسل. |
|
|  | [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | يضبط الحد الأقصى لارتفاع صورة الإخراج بالبكسل. |
|
|  | [getImageWidth()](#getImageWidth--) | يحصل على عرض الصورة الناتجة بالبكسل. |
|
|  | [setImageWidth(int imageWidth)](#setImageWidth-int-) | يضبط عرض الصورة الناتجة بالبكسل. |
|
|  | [getImageHeight()](#getImageHeight--) | يحصل على ارتفاع الصورة الناتجة بالبكسل عند تحويل صورة واحدة إلى HTML. |
|
|  | [setImageHeight(int imageHeight)](#setImageHeight-int-) | يضبط ارتفاع الصورة الناتجة بالبكسل عند تحويل صورة واحدة إلى HTML. |
|
|  | [isForPrinting()](#isForPrinting--) | يتحقق مما إذا كان يجب تحسين HTML الناتج للطباعة. |
|
|  | [setForPrinting(boolean value)](#setForPrinting-boolean-) | يضبط ما إذا كان يجب تحسين HTML الناتج للطباعة. |
|
|  | [isExcludeFonts()](#isExcludeFonts--) | يحدد ما إذا كان يجب استبعاد الخطوط من مستند HTML. |
|
|  | [setExcludeFonts(boolean value)](#setExcludeFonts-boolean-) | يضبط ما إذا كان يجب استبعاد الخطوط من مستند HTML. |
|
|  | [getFontsToExclude()](#getFontsToExclude--) | يسترجع قائمة أسماء الخطوط لاستبعادها من مستند HTML. |
|
|  | [setFontsToExclude(List<String> value)](#setFontsToExclude-java.util.List-java.lang.String--) | يضبط قائمة أسماء الخطوط لاستبعادها من مستند HTML. |
|
|  | [isRemoveJavaScript()](#isRemoveJavaScript--) | يسمح بإزالة شفرة JavaScript المصدرية من الروابط في مستندات HTML الناتجة، عند تحويل المستندات المدخلة التي تحتوي على السكريبتات. |
|
|  | [setRemoveJavaScript(boolean value)](#setRemoveJavaScript-boolean-) | يضبط الإذن لإزالة شفرة JavaScript المصدرية من الروابط في مستندات HTML الناتجة، عند تحويل المستندات المدخلة التي تحتوي على السكريبتات. |
|
|  | [getDocumentSavingCallback()](#getDocumentSavingCallback--) | يسترجع الدالة الراجعة المستخدمة لتقدير تقدم حفظ مستند Words أو Email. |
|
|  | [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | يضبط الدالة الراجعة المستخدمة لتقدير تقدم حفظ مستند Words أو Email. |
|
|  | [forEmbeddedResources(CreatePageStream createPageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.
|
|  | [forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.
|
|  | [forEmbeddedResources(PageStreamFactory pageStreamFactory)](#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.
|
|  | [forEmbeddedResources()](#forEmbeddedResources--) | ينشئ مثلاً جديداً من |
HtmlViewOptions
الفئة.
|
|  | [forEmbeddedResources(String filePathFormat)](#forEmbeddedResources-java.lang.String-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
الفئة.
|
|  | [forEmbeddedResources(Path filePathFormat)](#forEmbeddedResources-java.nio.file.Path-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
الفئة.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.
|
|  | [forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)](#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.
|
|  | [forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)](#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.
|
|  | [forExternalResources()](#forExternalResources--) | يُنشئ نسخة جديدة من |
HtmlViewOptions
الفئة.
|
|  | [forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)](#forExternalResources-java.lang.String-java.lang.String-java.lang.String-) | ينشئ مثلاً جديداً من |
HtmlViewOptions
الفئة.
|
### CREATE_PAGE_STREAM {#CREATE-PAGE-STREAM}
```
public static final String CREATE_PAGE_STREAM
```


### FILE_PATH_FORMAT {#FILE-PATH-FORMAT}
```
public static final String FILE_PATH_FORMAT
```


### isRenderResponsive() {#isRenderResponsive--}
```
public final boolean isRenderResponsive()
```


يحدد ما إذا كان العرض المتجاوب مفعّلاً.
تُظهر صفحات الويب المتجاوبة بشكل جيد على الأجهزة ذات أحجام الشاشات المختلفة.


يهدف التصميم المتجاوب إلى جعل صفحات الويب تُظهر بشكل جيد على مجموعة متنوعة من الأجهزة. لتطبيق تخطيط متجاوب، اضبط هذه الخاصية إلى true.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Returns:**
منطقي -  true  إذا كان العرض المتجاوب مفعلاً،  false  خلاف ذلك.

### setRenderResponsive(boolean value) {#setRenderResponsive-boolean-}
```
public final void setRenderResponsive(boolean value)
```


يضبط ما إذا كان العرض المتجاوب مفعّلاً.
تُظهر صفحات الويب المتجاوبة بشكل جيد على الأجهزة ذات أحجام الشاشات المختلفة.


يهدف التصميم المتجاوب إلى جعل صفحات الويب تُظهر بشكل جيد على مجموعة متنوعة من الأجهزة. لتطبيق تخطيط متجاوب، اضبط هذه الخاصية إلى true.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-with-responsive-layout/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين العرض المتجاوب،  false  لتعطيله. |
|

### isMinify() {#isMinify--}
```
public final boolean isMinify()
```


يتحقق مما إذا كان تقليل حجم محتوى HTML وموارد HTML مفعّلاً.


ضغط محتوى الإخراج (HTML، CSS، وSVG) هو أحد طرق تحسين ملف HTML. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Returns:**
منطقي -  true  إذا كان التصغير مفعلاً،  false  خلاف ذلك.

### setMinify(boolean value) {#setMinify-boolean-}
```
public final void setMinify(boolean value)
```


يضبط ما إذا كان تقليل حجم محتوى HTML وموارد HTML مفعّلاً.


ضغط محتوى الإخراج (HTML، CSS، وSVG) هو أحد طرق تحسين ملف HTML. للقيام بذلك، اضبط هذه الخاصية إلى true.
للحصول على مثال على الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/minify-html/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين التصغير،  false لتعطيله. |
|

### isRenderToSinglePage() {#isRenderToSinglePage--}
```
public boolean isRenderToSinglePage()
```


يُمكّن عرض المستند بالكامل إلى ملف HTML واحد.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Returns:**
boolean
### setRenderToSinglePage(boolean renderSinglePage) {#setRenderToSinglePage-boolean-}
```
public void setRenderToSinglePage(boolean renderSinglePage)
```


يُمكّن عرض المستند بالكامل إلى ملف HTML واحد.

**See the following topics for more information:**

* [Render archives as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-archive-files/#create-a-single-html-page)
* [Render text documents as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-text-files/#create-a-single-html-page)
* [Render Excel and Apple Numbers spreadsheets as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#convert-all-excel-worksheets-to-one-html-file)
* [Render web documents as PDF, PNG, and JPEG files](../https://docs.groupdocs.com/viewer/java/render-web-documents/#create-an-html-file-with-embedded-resources)

**Example:**


try (final Viewer viewer = new Viewer(\"invoice.docx\")) {
HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
viewOptions.setRenderToSinglePage(true);

viewer.view(viewOptions);
}
     


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderSinglePage | boolean |  |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


يعيد الحد الأقصى لعرض الصورة الناتجة بالبكسل.
***Note:** This value is used when converting a single image to HTML.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - الحد الأقصى لعرض صورة الإخراج.

### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


يضبط الحد الأقصى لعرض صورة الإخراج بالبكسل.
***Note:** This value is used when converting a single image to HTML.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageMaxWidth | int | الحد الأقصى لعرض صورة الإخراج. |
|

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


يحصل على الحد الأقصى لارتفاع الصورة الناتجة بالبكسل.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Returns:**
int - الحد الأقصى لارتفاع صورة الإخراج.

### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


يضبط الحد الأقصى لارتفاع صورة الإخراج بالبكسل.
***Note:** This option applies when converting a single image to HTML. It specifies the maximum height of the output image.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageMaxHeight | int | الحد الأقصى لارتفاع صورة الإخراج. |
|

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


يحصل على عرض الصورة الناتجة بالبكسل.


***Note:** This value is applicable only when converting a single image to HTML.*
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - عرض صورة الإخراج.

### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


يضبط عرض الصورة الناتجة بالبكسل.


***Note:** This value is applicable only when converting a single image to HTML.*
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageWidth | int | عرض صورة الإخراج. |
|

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


يحصل على ارتفاع الصورة الناتجة بالبكسل عند تحويل صورة واحدة إلى HTML.


للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Returns:**
int - ارتفاع الصورة الناتجة بالبكسل.

### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


يضبط ارتفاع الصورة الناتجة بالبكسل عند تحويل صورة واحدة إلى HTML.


للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-html/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | imageHeight | int | ارتفاع الصورة الناتجة بالبكسل. |
|

### isForPrinting() {#isForPrinting--}
```
public final boolean isForPrinting()
```


يتحقق مما إذا كان يجب تحسين HTML الناتج للطباعة.


فعّل هذا الخيار لتحويل صفحات HTML الناتجة إلى صيغة SVG المتجهة.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Returns:**
boolean -  true  إذا كان يجب تحسين HTML الناتج للطباعة،  false  خلاف ذلك.

### setForPrinting(boolean value) {#setForPrinting-boolean-}
```
public final void setForPrinting(boolean value)
```


يضبط ما إذا كان يجب تحسين HTML الناتج للطباعة.


فعّل هذا الخيار لتحويل صفحات HTML الناتجة إلى صيغة SVG المتجهة.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/how-to-optimize-output-html-for-printing/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتحسين HTML الناتج للطباعة،  false  خلاف ذلك. |
|

### isExcludeFonts() {#isExcludeFonts--}
```
public final boolean isExcludeFonts()
```


يحدد ما إذا كان يجب استبعاد الخطوط من مستند HTML.


بشكل افتراضي، يقوم GroupDocs.Viewer بدمج الخطوط المستخدمة في المستند داخل HTML. لمنع ذلك، اضبط هذه الخاصية إلى true.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
boolean -  true  إذا كان يجب استبعاد الخطوط،  false  خلاف ذلك.

### setExcludeFonts(boolean value) {#setExcludeFonts-boolean-}
```
public final void setExcludeFonts(boolean value)
```


يضبط ما إذا كان يجب استبعاد الخطوط من مستند HTML.


بشكل افتراضي، يقوم GroupDocs.Viewer بدمج الخطوط المستخدمة في المستند داخل HTML. لمنع ذلك، اضبط هذه الخاصية إلى true.
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لاستبعاد الخطوط،  false  خلاف ذلك. |
|

### getFontsToExclude() {#getFontsToExclude--}
```
public final List<String> getFontsToExclude()
```


يسترجع قائمة أسماء الخطوط لاستبعادها من مستند HTML.


هذا الخيار مدعوم للعرض التقديمي فقط.
إدراج الخطوط في مستند HTML يحسن استقرار العرض الناتج لكنه يزيد من حجم نتيجة التجسيد.
استخدم هذا الخيار لإيجاد تسوية بين الاستقرار وحجم الناتج.
تضمّن أسماء الخطوط الشائعة والمثبتة على معظم الأنظمة.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) الخيار معطل.*
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Returns:**
java.util.List<java.lang.String> - قائمة بأسماء الخطوط التي يجب استبعادها من مستند HTML.

### setFontsToExclude(List<String> value) {#setFontsToExclude-java.util.List-java.lang.String--}
```
public final void setFontsToExclude(List<String> value)
```


يضبط قائمة أسماء الخطوط لاستبعادها من مستند HTML.


هذا الخيار مدعوم للعرض التقديمي فقط.
إدراج الخطوط في مستند HTML يحسن استقرار العرض الناتج لكنه يزيد من حجم نتيجة التجسيد.
استخدم هذا الخيار لإيجاد تسوية بين الاستقرار وحجم الناتج.
تضمّن أسماء الخطوط الشائعة والمثبتة على معظم الأنظمة.


***Note:** Please note that this property is active only when the 
ExcludeFonts
(#isExcludeFonts().isExcludeFonts()/#setExcludeFonts(boolean).setExcludeFonts(boolean)) الخيار معطل.*
للتفاصيل ومثال على الشيفرة، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/exclude-fonts/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | java.util.List<java.lang.String> | قائمة بأسماء الخطوط التي يجب استبعادها من مستند HTML. |
|

### isRemoveJavaScript() {#isRemoveJavaScript--}
```
public final boolean isRemoveJavaScript()
```


يسمح بإزالة شفرة JavaScript المصدرية من الروابط في مستندات HTML الناتجة عند تحويل المستندات المدخلة التي تحتوي على السكريبتات. يكون مفعلاً افتراضيًا (true).


للتفاصيل حول إزالة JavaScript، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Returns:**
boolean
### setRemoveJavaScript(boolean value) {#setRemoveJavaScript-boolean-}
```
public void setRemoveJavaScript(boolean value)
```


يضبط الإذن لإزالة شفرة JavaScript المصدرية من الروابط في مستندات HTML الناتجة عند تحويل المستندات المدخلة التي تحتوي على السكريبتات. يكون مفعلاً افتراضيًا (true).


للتفاصيل حول إزالة JavaScript، راجع [الوثائق](../https://docs.groupdocs.com/viewer/net/rendering-to-html/#preserving-or-disabling-javascript-when-rendering-to-html).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | boolean |  |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


يسترجع الدالة الراجعة المستخدمة لتقدير تقدم حفظ مستند Words أو Email.


**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - رد النداء المستخدم لتقدير تقدم حفظ المستند.

### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


يضبط الدالة الراجعة المستخدمة لتقدير تقدم حفظ مستند Words أو Email.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | رد النداء المستخدم لتقدير تقدم حفظ المستند. |
|

### forEmbeddedResources(CreatePageStream createPageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.


***Note:** The method takes a 
CreatePageStream
معامل، وهو طريقة تُستخدم لإنشاء تدفق لكتابة بيانات الصفحة الناتجة.*
للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تُنشئ تدفقًا يُستخدم لكتابة بيانات الصفحة الناتجة. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public static HtmlViewOptions forEmbeddedResources(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تُنشئ تدفقًا يُستخدم لكتابة بيانات الصفحة الناتجة. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | الطريقة التي تُطلق التدفق الذي أنشأته الطريقة المعينة للمعامل  createPageStream  . |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources(PageStreamFactory pageStreamFactory) {#forEmbeddedResources-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public static HtmlViewOptions forEmbeddedResources(PageStreamFactory pageStreamFactory)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد مدمجة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء وإطلاق تدفق الصفحة الناتجة. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with embedded resources.

### forEmbeddedResources() {#forEmbeddedResources--}
```
public static HtmlViewOptions forEmbeddedResources()
```


ينشئ مثلاً جديداً من
HtmlViewOptions
الفئة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(String filePathFormat) {#forEmbeddedResources-java.lang.String-}
```
public static HtmlViewOptions forEmbeddedResources(String filePathFormat)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
الفئة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | تنسيق مسار الملف، مثال: 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forEmbeddedResources(Path filePathFormat) {#forEmbeddedResources-java.nio.file.Path-}
```
public static HtmlViewOptions forEmbeddedResources(Path filePathFormat)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
الفئة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-embedded-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.nio.file.Path | تنسيق مسار الملف، مثال: 'page_{0}.html'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.


***Note:** This method should be used when rendering HTML with external resources, such as CSS and JavaScript files.*
للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تُنشئ التدفق المستخدم لكتابة بيانات الصفحة الناتجة. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | الطريقة التي تُطلق التدفق الذي أنشأته طريقة  createPageStream . |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | الطريقة التي تُنشئ عنوان URL لمورد HTML. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream) {#forExternalResources-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.CreateResourceStream-com.groupdocs.viewer.interfaces.CreateResourceUrl-com.groupdocs.viewer.interfaces.ReleasePageStream-com.groupdocs.viewer.interfaces.ReleaseResourceStream-}
```
public static HtmlViewOptions forExternalResources(CreatePageStream createPageStream, CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | الطريقة التي تُنشئ التدفق المستخدم لكتابة بيانات الصفحة الناتجة. |
|
|  | createResourceStream | [CreateResourceStream](../../com.groupdocs.viewer.interfaces/createresourcestream) | الطريقة التي تُنشئ التدفق المستخدم لكتابة بيانات مورد HTML الناتج. |
|
|  | createResourceUrl | [CreateResourceUrl](../../com.groupdocs.viewer.interfaces/createresourceurl) | الطريقة التي تُنشئ عنوان URL لمورد HTML. |
|
|  | releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | الطريقة التي تُطلق التدفق الذي أنشأته طريقة  createPageStream . |
|
|  | releaseResourceStream | [ReleaseResourceStream](../../com.groupdocs.viewer.interfaces/releaseresourcestream) | الطريقة التي تُطلق التدفق الذي أنشأته طريقة  createResourceStream . |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory) {#forExternalResources-com.groupdocs.viewer.interfaces.PageStreamFactory-com.groupdocs.viewer.interfaces.ResourceStreamFactory-}
```
public static HtmlViewOptions forExternalResources(PageStreamFactory pageStreamFactory, ResourceStreamFactory resourceStreamFactory)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
فئة لتحويل إلى HTML مع موارد خارجية.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء وإطلاق تدفق الصفحة الناتجة. |
|
|  | resourceStreamFactory | [ResourceStreamFactory](../../com.groupdocs.viewer.interfaces/resourcestreamfactory) | المصنع الذي يطبق طرقًا لإنشاء عناوين URL للموارد وتكوين/إطلاق تدفق مورد HTML الناتج. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions) - a new instance of the  HtmlViewOptions  class for rendering into HTML with external resources.

### forExternalResources() {#forExternalResources--}
```
public static HtmlViewOptions forExternalResources()
```


يُنشئ نسخة جديدة من
HtmlViewOptions
الفئة.


* - with "p_{0}.html" as file path format for the output HTML files;
* - with "p_{0}_{1}" as file path format for the output HTML-resource files;
* - with "p_{0}_{1}" as URL format for HTML-resources;

ستُوضع ملفات الإخراج في دليل العمل الحالي للتطبيق. للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).

<br />



**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
### forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat) {#forExternalResources-java.lang.String-java.lang.String-java.lang.String-}
```
public static HtmlViewOptions forExternalResources(String filePathFormat, String resourceFilePathFormat, String resourceUrlFormat)
```


ينشئ مثلاً جديداً من
HtmlViewOptions
الفئة.


للحصول على مثال الكود، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/rendering-to-html/#rendering-to-html-with-external-resources).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | تنسيق مسار الملف، مثال: 'page_{0}.html'. |
|
|  | resourceFilePathFormat | java.lang.String | تنسيق مسار ملف المورد، مثال: 'page_{0}/resource_{1}'. |
|
|  | resourceUrlFormat | java.lang.String | تنسيق عنوان URL للمورد، مثال: 'page_{0}/resource_{1}'. |
|

**Returns:**
[HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions)
