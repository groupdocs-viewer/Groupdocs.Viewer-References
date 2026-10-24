---
title: "Tile"
second_title: "GroupDocs.Viewer لـ Java مرجع API"
description: "يمثل منطقة الرسم."
type: docs
weight: 33
url: /ar/java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

يمثل منطقة الرسم.


تمثل فئة Tile منطقة رسم في مكوّن GroupDocs.Viewer.
يُستخدم لتحديد منطقة أو قطاع محدد داخل مستند يحتاج إلى أن يُعرض أو يُعالج بشكل منفصل.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


مثال على الاستخدام:

````

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## المنشئات

| منشئ | الوصف |
| --- | --- |
|  | [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | ينشئ مثلاً جديداً من |
Tile
الفئة.
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getStartPointX()](#getStartPointX--) | يحصل على إحداثي X لأدنى نقطة يسرى في الرسم حيث يبدأ الـtile. |
|
|  | [getStartPointY()](#getStartPointY--) | يحصل على إحداثي Y للنقطة اليسرى السفلية في الرسم حيث يبدأ البلاط. |
|
|  | [getWidth()](#getWidth--) | يحصل على عرض البلاط بالبكسل. |
|
|  | [getHeight()](#getHeight--) | يحصل على ارتفاع البلاط بالبكسل. |
|
|  | [getEndPointX()](#getEndPointX--) | يعيد إحداثي X للنقطة اليمنى العليا في الرسم حيث ينتهي البلاط. |
|
|  | [getEndPointY()](#getEndPointY--) | يعيد إحداثي Y للنقطة اليمنى العليا في الرسم حيث ينتهي البلاط. |
|
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


ينشئ مثلاً جديداً من
Tile
الفئة.


يقوم هذا المُنشئ بإنشاء كائن بلاط جديد بالنقطة الابتدائية المحددة والعرض والارتفاع.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | startPointX | int | إحداثي X للنقطة اليسرى السفلية في الرسم حيث يبدأ البلاط. |
|
|  | startPointY | int | إحداثي Y للنقطة اليسرى السفلية في الرسم حيث يبدأ البلاط. |
|
|  | width | int | عرض البلاط بالبكسل. |
|
|  | ارتفاع | int | ارتفاع البلاط بالبكسل. |
|

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


يحصل على إحداثي X لأدنى نقطة يسرى في الرسم حيث يبدأ الـtile.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - إحداثي X للنقطة اليسرى السفلية.

### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


يحصل على إحداثي Y للنقطة اليسرى السفلية في الرسم حيث يبدأ البلاط.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - إحداثي Y للنقطة اليسرى السفلية.

### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض البلاط بالبكسل.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - عرض البلاط.

### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع البلاط بالبكسل.
للتفاصيل، راجع [الوثائق](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles).


**Returns:**
int - ارتفاع البلاط.

### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


يعيد إحداثي X للنقطة اليمنى العليا في الرسم حيث ينتهي البلاط.


**Returns:**
int - إحداثي X للنقطة اليمنى العليا.

### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


يعيد إحداثي Y للنقطة اليمنى العليا في الرسم حيث ينتهي البلاط.


**Returns:**
int - إحداثي Y للنقطة اليمنى العليا.

