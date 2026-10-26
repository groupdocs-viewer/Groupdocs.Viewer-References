---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يوفر خيارات لعرض خيارات العروض التقديمية."
type: docs
weight: 26
url: /ar/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

يوفر خيارات لعرض خيارات العروض التقديمية.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | يفعل وضعًا جديدًا لتصيير HTML لمستندات Presentation. |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | يفعل وضعًا جديدًا لتصيير HTML لمستندات Presentation. |
| [getResolution()](#getResolution--) | دقة الصور داخل presentation (للتصيير إلى HTML/PDF فقط). |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | دقة الصور داخل presentation (للتصيير إلى HTML/PDF فقط). |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


يفعل وضعًا جديدًا لتصيير HTML لمستندات Presentation.

في هذا الوضع، يتم تصيير ملفات Presentation إلى ترميز HTML/CSS نقي، دون صور SVG. بشكل افتراضي، تكون هذه الميزة معطلة (false). يُستخدم المصيّر HTML القائم على SVG إذا لم يتم تمكين هذا الخيار.

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


يفعل وضعًا جديدًا لتصيير HTML لمستندات Presentation.

في هذا الوضع، يتم تصيير ملفات Presentation إلى ترميز HTML/CSS نقي، دون صور SVG. بشكل افتراضي، تكون هذه الميزة معطلة (false). يُستخدم المصيّر HTML القائم على SVG إذا لم يتم تمكين هذا الخيار.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


دقة الصور داخل presentation (للتصيير إلى HTML/PDF فقط).

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


دقة الصور داخل presentation (للتصيير إلى HTML/PDF فقط).

لعينة الكود، انظر إلى [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

