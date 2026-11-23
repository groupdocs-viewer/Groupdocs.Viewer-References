---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يحتوي على خيارات لتصيير مستندات Visio."
type: docs
weight: 36
url: /ar/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

يحتوي على خيارات لتصيير مستندات Visio.


توفر فئة VisioRenderingOptions خيارات لمعالجة وعرض ملفات Visio
في مكوّن GroupDocs.Viewer. إنها تغلف الإعدادات والمعلمات التي يمكن استخدامها
للتحكم في عملية العرض وتنسيق الإخراج لمستندات Visio.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-visio-documents/).


مثال على الاستخدام:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | ينشئ مثلاً جديداً من |
VisioRenderingOptions
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | اعرض فقط أشكال Visio، مع استبعاد المخطط. |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | يضبط العلامة لعرض أشكال Visio فقط، مع استبعاد المخطط. |
|
|  | [getFigureWidth()](#getFigureWidth--) | يسترجع عرض الشكل. |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | يضبط عرض الشكل. |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


ينشئ مثلاً جديداً من
VisioRenderingOptions
الفئة.


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


اعرض فقط أشكال Visio، مع استبعاد المخطط.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Returns:**
boolean -  true  إذا كان يجب عرض أشكال Visio فقط،  false  خلاف ذلك.

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


يضبط العلامة لعرض أشكال Visio فقط، مع استبعاد المخطط.
للتفاصيل، راجع [التوثيق](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  لعرض أشكال Visio فقط،  false  لتضمين المخطط. |
|

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


يضبط عرض الشكل. سيتم حساب الارتفاع تلقائيًا.


***Note:** Default value is 100.*


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | figureWidth | int | عرض الشكل. |
|

