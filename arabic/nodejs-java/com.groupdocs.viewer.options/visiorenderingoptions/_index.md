---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يحتوي على خيارات لتصيير مستندات Visio."
type: docs
weight: 36
url: /ar/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

يحتوي على خيارات لتصيير مستندات Visio.

توفر فئة VisioRenderingOptions خيارات لمعالجة وعرض ملفات Visio في مكوّن GroupDocs.Viewer. تُجَمِّع الإعدادات والمعلمات التي يمكن استخدامها للتحكم في عملية العرض وتنسيق الإخراج لمستندات Visio. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | ينشئ مثيلًا جديدًا من فئة VisioRenderingOptions. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | اعرض فقط أشكال Visio، مستثنيًا المخطط. |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | يضبط العلامة لعرض أشكال Visio فقط، مستثنيًا المخطط. |
| [getFigureWidth()](#getFigureWidth--) | يسترجع عرض الشكل. |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | يضبط عرض الشكل. |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


ينشئ مثيلًا جديدًا من فئة VisioRenderingOptions.

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


اعرض فقط أشكال Visio، مستثنيًا المخطط.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
منطقي - true إذا كان يجب عرض رسومات Visio فقط، false خلاف ذلك.
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


يضبط العلامة لعرض أشكال Visio فقط، مستثنيًا المخطط.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| renderFiguresOnly | boolean | true لعرض رسومات Visio فقط، false لتضمين المخطط. |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


يسترجع عرض الشكل. سيتم حساب الارتفاع تلقائيًا.

**Returns:**
int - عرض الشكل.
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


يحدد عرض الشكل. سيتم حساب الارتفاع تلقائيًا.

***Note:** Default value is 100.*

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| figureWidth | int | عرض الشكل. |

