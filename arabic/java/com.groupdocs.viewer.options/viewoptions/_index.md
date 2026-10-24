---
title: "ViewOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على خيارات التصيير."
type: docs
weight: 35
url: /ar/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

يحتوي على خيارات التصيير.


الفئة ViewOptions تمتد من الفئة BaseViewOptions وتعمل كفئة أساسية لخيارات العرض
في مكوّن GroupDocs.Viewer. إنه يضم إعدادات ومعلمات شائعة يمكن استخدامها
لعرض أنواع مختلفة من المستندات بصيغ متعددة.


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | يحصل على العلامة المائية النصية المطبقة على كل صفحة. |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | يضبط العلامة المائية النصية لتُطبق على كل صفحة. |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | يطبق دورانًا باتجاه عقارب الساعة على الصفحة المحددة. |
|
|  | [getPageRotations()](#getPageRotations--) | يسترجع دورانات الصفحات. |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | لتجنب إنشاء النسخة فقط للتحقق من أنها فارغة |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


يحصل على العلامة المائية النصية المطبقة على كل صفحة.


في حال تم تحديد كل من #setWatermark(Watermark).setWatermark(Watermark) و #getPageRotations().getPageRotations()،
ستُطبق العلامة المائية على الصفحات المدورة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


يضبط العلامة المائية النصية لتُطبق على كل صفحة.


في حال كلا
ViewOptions.Watermark
و #getPageRotations().getPageRotations() تم تحديدهما،
ستُطبق العلامة المائية على الصفحات المدورة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/add-text-watermark/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | العلامة المائية النصية التي سيتم تعيينها. |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


يطبق دورانًا باتجاه عقارب الساعة على الصفحة المحددة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | pageNumber | int | رقم الصفحة، يجب أن يكون أكبر من 0 بشكل صارم. |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | قيمة الدوران. |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


يسترجع دورانات الصفحات.


إذا تم تحديد كل من [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) و
getPageRotations()
تم تحديدها،
ستُطبق العلامة المائية على الصفحات المدورة.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/).


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - خريطة تحتوي على أرقام الصفحات كمفاتيح وتدويراتها المقابلة كقيم.

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


لتجنب إنشاء النسخة فقط للتحقق من أنها فارغة


**Returns:**
boolean
