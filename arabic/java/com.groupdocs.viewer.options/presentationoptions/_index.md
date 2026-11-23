---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يوفر خيارات لتصيير العروض التقديمية."
type: docs
weight: 26
url: /ar/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

يوفر خيارات لتصيير العروض التقديمية.


للحصول على تفاصيل، راجع [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | يفعل وضع تصيير HTML جديد لمستندات Presentation. |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | يفعل وضع تصيير HTML جديد لمستندات Presentation. |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | يفعل عرض العناصر النائبة في ترويسة وتذييل الشريحة. |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | يفعل عرض العناصر النائبة في ترويسة وتذييل الشريحة. |
|
|  | [getResolution()](#getResolution--) | الدقة للصور داخل العرض التقديمي (للتصيير إلى HTML/PDF فقط). |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | الدقة للصور داخل العرض التقديمي (للتصيير إلى HTML/PDF فقط). |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


يفعل وضع تصيير HTML جديد لمستندات Presentation.


في هذا الوضع، يتم تصيير ملفات Presentation إلى ترميز HTML/CSS نقي، دون صور SVG.
بشكل افتراضي، تكون هذه الميزة معطلة (false). يُستخدم المصرف HTML القائم على SVG إذا لم يتم تفعيل هذا الخيار.


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


يفعل وضع تصيير HTML جديد لمستندات Presentation.


في هذا الوضع، يتم تصيير ملفات Presentation إلى ترميز HTML/CSS نقي، دون صور SVG.
بشكل افتراضي، تكون هذه الميزة معطلة (false). يُستخدم المصرف HTML القائم على SVG إذا لم يتم تفعيل هذا الخيار.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


يمكن تمكين عرض العناصر النائبة في ترويسة وتذييل الشريحة. معطل بشكل افتراضي (false). ينطبق هذا الخيار على جميع أوضاع العرض الأربعة للعرض التقديمي: HTML، PDF، PNG، و JPEG. لا ينطبق عند عرض العرض التقديمي إلى ترميز HTML/CSS نقي باستخدام .


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


يمكن تمكين عرض العناصر النائبة في ترويسة وتذييل الشريحة. معطل بشكل افتراضي (false). ينطبق هذا الخيار على جميع أوضاع العرض الأربعة للعرض التقديمي: HTML، PDF، PNG، و JPEG. لا ينطبق عند عرض العرض التقديمي إلى ترميز HTML/CSS نقي باستخدام .


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


الدقة للصور داخل العرض التقديمي (للتصيير إلى HTML/PDF فقط).


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


الدقة للصور داخل العرض التقديمي (للتصيير إلى HTML/PDF فقط).


لعينة الشيفرة، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

