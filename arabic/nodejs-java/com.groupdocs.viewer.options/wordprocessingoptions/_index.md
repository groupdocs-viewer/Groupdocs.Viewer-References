---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لتصيير مستندات معالجة الكلمات."
type: docs
weight: 38
url: /ar/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

يوفر خيارات لتصيير مستندات معالجة الكلمات.

توفر فئة WordProcessingOptions خيارات لتصيير مستندات معالجة النصوص في مكوّن GroupDocs.Viewer. إنها تغلف الإعدادات والمعلمات التي يمكن استخدامها للتحكم في عملية التصيير وتنسيق الإخراج لملفات معالجة النصوص. للتفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | ينشئ مثيلًا جديدًا من الفئة WordProcessingOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPageSize()](#getPageSize--) | يسترجع حجم الصفحة لتصيير ملفات HTM وHTML. |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | يضبط حجم الصفحة لتصيير ملفات HTM وHTML. |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | يشير إلى ما إذا كان تصيير التغييرات المتتبعة (المراجعات) مفعلاً. |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | يضبط ما إذا كان تصيير التغييرات المتتبعة (المراجعات) مفعلاً. |
| [getLeftMargin()](#getLeftMargin--) | يسترجع الهامش الأيسر للصفحة لتصيير HTML. |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | يضبط الهامش الأيسر للصفحة لتصيير HTML. |
| [getRightMargin()](#getRightMargin--) | يسترجع الهامش الأيمن للصفحة لتصيير HTML. |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | يضبط الهامش الأيمن للصفحة لتصيير HTML. |
| [getTopMargin()](#getTopMargin--) | يسترجع الهامش العلوي للصفحة لتصيير HTML. |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | يضبط هامش الصفحة العلوي لتصوير HTML. |
| [getBottomMargin()](#getBottomMargin--) | هامش الصفحة السفلي (لتصوير HTML فقط) |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | يضبط هامش الصفحة السفلي لتصوير HTML. |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | هذا الخيار يفعّل ضبط الحروف (kerning) وميزات OpenType الأخرى عند تصوير النصوص العربية أو العبرية أو الهندية أو النصوص المستندة إلى اللاتينية أو السيريالية. |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | هذا الخيار يفعّل ضبط الحروف (kerning) وميزات OpenType الأخرى عند تصوير النصوص العربية أو العبرية أو الهندية أو النصوص المستندة إلى اللاتينية أو السيريالية. |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التصوير إلى HTML أو PDF. |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | يضبط ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التصوير إلى HTML أو PDF. |
| [isUpdateFields()](#isUpdateFields--) | يحصل على قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند معالجة الكلمات المدخل إلى صيغ الإخراج HTML أو PDF أو PNG أو JPEG. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | يضبط قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند معالجة الكلمات المدخل إلى صيغ الإخراج HTML أو PDF أو PNG أو JPEG. |
| [equals(Object o)](#equals-java.lang.Object-) | تحقق مما إذا تم تغيير الخيارات. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


يُنشئ مثيلاً جديدًا من الفئة  WordProcessingOptions . يحتوي على خيارات لتصوير مستندات معالجة الكلمات. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


يسترجع حجم الصفحة لتصيير ملفات HTM وHTML.

عند استخدام حجم الصفحة الافتراضي، قد لا يتناسب بعض المحتوى مع إطار الصفحة. لتناسب المحتوى، يمكنك ضبط حجم صفحة أكبر، مثل A3، باستخدام [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


يضبط حجم الصفحة لتصيير ملفات HTM وHTML.

عند استخدام حجم الصفحة الافتراضي، قد لا يتناسب بعض المحتوى مع إطار الصفحة. لتناسب المحتوى، يمكنك ضبط حجم صفحة أكبر، مثل A3، باستخدام [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\\#A3).

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | حجم صفحة الإخراج. |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


يشير إلى ما إذا كان تصيير التغييرات المتتبعة (المراجعات) مفعلاً.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
منطقي -  true  إذا كان تصوير التغييرات المتتبعة مفعلاً،  false  خلاف ذلك.
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


يضبط ما إذا كان تصيير التغييرات المتتبعة (المراجعات) مفعلاً.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | boolean | true  لتمكين تصوير التغييرات المتتبعة،  false  لتعطيله. |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


يسترجع الهامش الأيسر للصفحة لتصيير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - قيمة هامش الصفحة الأيسر.
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


يضبط الهامش الأيسر للصفحة لتصيير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| leftMargin | java.lang.Double | قيمة هامش الصفحة الأيسر لتعيينها. |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


يسترجع الهامش الأيمن للصفحة لتصيير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - قيمة هامش الصفحة الأيمن.
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


يضبط الهامش الأيمن للصفحة لتصيير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| rightMargin | java.lang.Double | قيمة هامش الصفحة الأيمن لتعيينها. |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


يسترجع الهامش العلوي للصفحة لتصيير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - هامش الصفحة العلوي.
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


يضبط هامش الصفحة العلوي لتصوير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| topMargin | java.lang.Double | هامش الصفحة العلوي لتعيينه. |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


هامش الصفحة السفلي (لتصوير HTML فقط)

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - هامش الصفحة السفلي.
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


يضبط هامش الصفحة السفلي لتصوير HTML.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| bottomMargin | java.lang.Double | هامش الصفحة السفلي لتعيينه. |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


هذا الخيار يفعّل ضبط الحروف (kerning) وميزات OpenType الأخرى عند تصوير النصوص العربية أو العبرية أو الهندية أو النصوص المستندة إلى اللاتينية أو السيريالية.

**Returns:**
منطقي - True إذا كانت ميزات OpenType مفعلة، false خلاف ذلك.
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


هذا الخيار يفعّل ضبط الحروف (kerning) وميزات OpenType الأخرى عند تصوير النصوص العربية أو العبرية أو الهندية أو النصوص المستندة إلى اللاتينية أو السيريالية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | True لتمكين ميزات OpenType، false خلاف ذلك. |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التحويل إلى HTML أو PDF. عندما يتم تعيين هذا الخيار إلى true، بالنسبة إلى التحويل إلى HTML، سيتم استبدال الروابط النسبية من جدول المحتويات بعناصر span، مما يزيل الوظيفة لكن يحافظ على المظهر البصري. بالنسبة إلى التحويل إلى PDF، سيتم عرض جدول المحتويات كنص عادي دون روابط.

**Returns:**
منطقي - True إذا تم تعطيل تنقل جدول المحتويات؛ وإلا، false.
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


يحدد ما إذا كان يجب تعطيل تنقل جدول المحتويات عند التحويل إلى HTML أو PDF. عندما يتم تعيين هذا الخيار إلى true، بالنسبة إلى التحويل إلى HTML، سيتم استبدال الروابط النسبية من جدول المحتويات بعناصر span، مما يزيل الوظيفة لكن يحافظ على المظهر البصري. بالنسبة إلى التحويل إلى PDF، سيتم عرض جدول المحتويات كنص عادي دون روابط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| unlinkTableOfContents | boolean | يشير إلى ما إذا كان يجب تعطيل تنقل جدول المحتويات. |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


يحصل على قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند WordProcessing المدخل إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية لهذه الخاصية هي true \\u2014 سيتم تحديث الحقول قبل الحفظ.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


يضبط قيمة تحدد ما إذا كان يجب تحديث الحقول من أنواع معينة قبل حفظ مستند WordProcessing المدخل إلى صيغ HTML أو PDF أو PNG أو JPEG. القيمة الافتراضية لهذه الخاصية هي true \\u2014 سيتم تحديث الحقول قبل الحفظ.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


تحقق مما إذا تم تغيير الخيارات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| o | java.lang.Object | الكائن للمقارنة من حيث المساواة. |

**Returns:**
منطقي -  true  إذا كانت الخيارات مساوية للكائن المحدد،  false  خلاف ذلك.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يحسب قيمة رمز التجزئة لهذا الكائن. رمز التجزئة يعتمد على الحالة الداخلية للكائن ويُستخدم في هياكل البيانات القائمة على التجزئة مثل خرائط التجزئة ومجموعات التجزئة.

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - قيمة رمز التجزئة لهذا الكائن.
