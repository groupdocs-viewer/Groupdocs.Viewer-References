---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير مستندات معالجة الكلمات."
type: docs
weight: 38
url: /ar/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

يوفر خيارات لتصيير مستندات معالجة الكلمات.


توفر فئة WordProcessingOptions خيارات لعرض مستندات معالجة النصوص
في مكوّن GroupDocs.Viewer. إنها تغلف الإعدادات والمعلمات التي يمكن استخدامها
للتحكم في عملية العرض وتنسيق الإخراج لملفات معالجة النصوص.
للحصول على تفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


مثال على الاستخدام:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | ينشئ مثلاً جديداً من |
WordProcessingOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | يسترجع حجم الصفحة لعرض ملفات HTM وHTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | يضبط حجم الصفحة لعرض ملفات HTM وHTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | يشير إلى ما إذا كان عرض التغييرات المتتبعة (المراجعات) مفعلاً. |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | يضبط ما إذا كان عرض التغييرات المتتبعة (المراجعات) مفعلاً. |
|
|  | [getLeftMargin()](#getLeftMargin--) | يسترجع هامش الصفحة الأيسر لعرض HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | يضبط هامش الصفحة الأيسر لعرض HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | يحصل على هامش الصفحة الأيمن لعرض HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | يضبط الهامش الأيمن للصفحة لتص rendering HTML. |
|
|  | [getTopMargin()](#getTopMargin--) | يسترجع الهامش العلوي للصفحة لتص rendering HTML. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | يضبط الهامش العلوي للصفحة لتص rendering HTML. |
|
|  | [getBottomMargin()](#getBottomMargin--) | الهامش السفلي للصفحة (لتص rendering HTML فقط) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | يضبط الهامش السفلي للصفحة لتص rendering HTML. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | تُمكّن هذه الخيار من تمكين الـ kerning وميزات OpenType الأخرى عند تص rendering العربية أو العبرية أو الخطوط الهندية أو الخطوط المستندة إلى اللاتينية أو السيريالية. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | تُمكّن هذه الخيار من تمكين الـ kerning وميزات OpenType الأخرى عند تص rendering العربية أو العبرية أو الخطوط الهندية أو الخطوط المستندة إلى اللاتينية أو السيريالية. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التص rendering إلى HTML أو PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | يضبط ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التص rendering إلى HTML أو PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | يحصل على قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند معالجة الكلمات المدخل إلى صيغ الإخراج HTML أو PDF أو PNG أو JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | يضبط قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند معالجة الكلمات المدخل إلى صيغ الإخراج HTML أو PDF أو PNG أو JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | يحصل على الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | يحصل على الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | يسمح بفرض تطبيق ترقيم الصفحات للمستند المعالجة الكلمات المحمل. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | يسمح بفرض تطبيق ترقيم الصفحات للمستند المعالجة الكلمات المحمل. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا تم تغيير الخيارات. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


ينشئ مثلاً جديداً من
WordProcessingOptions
الفئة.
يحتوي على خيارات لتص rendering مستندات معالجة الكلمات. للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


يسترجع حجم الصفحة لعرض ملفات HTM وHTML.


عند استخدام حجم الصفحة الافتراضي، قد لا يتناسب بعض المحتوى مع إطار الصفحة.
لتناسب المحتوى، يمكنك ضبط حجم صفحة أكبر، مثل A3، باستخدام [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


يضبط حجم الصفحة لعرض ملفات HTM وHTML.


عند استخدام حجم الصفحة الافتراضي، قد لا يتناسب بعض المحتوى مع إطار الصفحة.
لتناسب المحتوى، يمكنك ضبط حجم صفحة أكبر، مثل A3، باستخدام [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | حجم الصفحة الناتجة. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


يشير إلى ما إذا كان عرض التغييرات المتتبعة (المراجعات) مفعلاً.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
منطقي -  true  إذا كان تمكين تص rendering التغييرات المتعقبة،  false  خلاف ذلك.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


يضبط ما إذا كان عرض التغييرات المتتبعة (المراجعات) مفعلاً.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | القيمة | boolean | true  لتمكين تص rendering التغييرات المتعقبة،  false  لتعطيله. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


يسترجع هامش الصفحة الأيسر لعرض HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - قيمة الهامش الأيسر للصفحة.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


يضبط هامش الصفحة الأيسر لعرض HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | قيمة الهامش الأيسر للصفحة لتعيينها. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


يحصل على هامش الصفحة الأيمن لعرض HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - قيمة هامش الصفحة اليمنى.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


يضبط الهامش الأيمن للصفحة لتص rendering HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | قيمة هامش الصفحة اليمنى لتعيينها. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


يسترجع الهامش العلوي للصفحة لتص rendering HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - هامش الصفحة العلوي.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


يضبط الهامش العلوي للصفحة لتص rendering HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | topMargin | java.lang.Double | هامش الصفحة العلوي لتعيينه. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


الهامش السفلي للصفحة (لتص rendering HTML فقط)
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - هامش الصفحة السفلي.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


يضبط الهامش السفلي للصفحة لتص rendering HTML.
للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | هامش الصفحة السفلي لتعيينه. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


تُمكّن هذه الخيار من تمكين الـ kerning وميزات OpenType الأخرى عند تص rendering العربية أو العبرية أو الخطوط الهندية أو الخطوط المستندة إلى اللاتينية أو السيريالية.


**Returns:**
boolean - True إذا كانت ميزات OpenType مفعلة، وإلا false.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


تُمكّن هذه الخيار من تمكين الـ kerning وميزات OpenType الأخرى عند تص rendering العربية أو العبرية أو الخطوط الهندية أو الخطوط المستندة إلى اللاتينية أو السيريالية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | True لتمكين ميزات OpenType، وإلا false. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التحويل إلى HTML أو PDF. عندما يتم تعيين هذا الخيار إلى true، بالنسبة للتحويل إلى HTML، سيتم استبدال الروابط النسبية من جدول المحتويات بعناصر span، مما يزيل الوظيفة لكن يحافظ على المظهر البصري. بالنسبة للتحويل إلى PDF، سيتم عرض جدول المحتويات كنص عادي دون روابط.


**Returns:**
boolean - True إذا تم تعطيل تنقل جدول المحتويات؛ وإلا false.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


يضبط ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التحويل إلى HTML أو PDF. عندما يتم تعيين هذا الخيار إلى true، بالنسبة للتحويل إلى HTML، سيتم استبدال الروابط النسبية من جدول المحتويات بعناصر span، مما يزيل الوظيفة لكن يحافظ على المظهر البصري. بالنسبة للتحويل إلى PDF، سيتم عرض جدول المحتويات كنص عادي دون روابط.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


يحصل على قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند WordProcessing المدخل إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية لهذه الخاصية هي true \\u2014 سيتم تحديث الحقول قبل الحفظ.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


يضبط قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند WordProcessing المدخل إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية لهذه الخاصية هي true \\u2014 سيتم تحديث الحقول قبل الحفظ.


للتفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


يحصل على الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تحويل مستندات WordProcessing إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Returns:**
int - الدقة الأفقية بوحدة DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


يضبط الدقة الأفقية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تحويل مستندات WordProcessing إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | horizontalResolution | int | الدقة الأفقية بوحدة DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


يحصل على الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تحويل مستندات WordProcessing إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Returns:**
int - الدقة العمودية بوحدة DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


يضبط الدقة العمودية للصور المولدة بوحدة النقاط في البوصة. يُستخدم هذا الخيار عند تحويل مستندات WordProcessing إلى صيغ PNG أو JPEG فقط.


القيمة الافتراضية هي 96 DPI. الحد الأدنى الممكن هو 72 DPI، والحد الأقصى الممكن هو 600 DPI.
إذا كانت القيمة المحددة من قبل المستخدم خارج هذه الحدود، سيتم تطبيق الحد الأدنى أو الحد الأقصى الممكن.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | verticalResolution | int | الدقة العمودية بوحدة DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


يسمح بفرض تطبيق ترقيم الصفحات على مستند WordProcessing المحمّل. بشكل افتراضي هو [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 المستند يبقى كما هو.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


يسمح بفرض تطبيق ترقيم الصفحات على مستند WordProcessing المحمّل. بشكل افتراضي هو [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 المستند يبقى كما هو.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | موقع رقم الصفحة. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا تم تغيير الخيارات.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | o | java.lang.Object | الكائن للمقارنة من حيث المساواة. |
|

**Returns:**
boolean -  true  إذا كانت الخيارات مساوية للكائن المحدد،  false  خلاف ذلك.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسب قيمة رمز التجزئة لهذا الكائن. رمز التجزئة يعتمد على
الحالة الداخلية للكائن ويستخدم في هياكل البيانات القائمة على التجزئة
مثل خرائط التجزئة ومجموعات التجزئة.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
عدد صحيح - قيمة رمز التجزئة لهذا الكائن.

