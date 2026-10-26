---
title: "Tile"
second_title: "GroupDocs.Viewer لـ Node.js عبر مرجع API للجاڤا"
description: "يمثل منطقة الرسم."
type: docs
weight: 33
url: /ar/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

يمثل منطقة الرسم.

تمثل فئة Tile منطقة رسم في مكوّن GroupDocs.Viewer. تُستخدم لتحديد منطقة أو جزء محدد داخل المستند يحتاج إلى العرض أو المعالجة بشكل منفصل. للحصول على تفاصيل، راجع [documentation][].

مثال على الاستخدام:

```

 Tile tile = new Tile(100, 100, 200, 200);

 PngViewOptions pngViewOptions = new PngViewOptions();
 pngViewOptions.getCadOptions().setTiles(Arrays.asList(tile));

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | يُنشئ مثيلًا جديدًا من فئة Tile. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | يحصل على إحداثي X لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile. |
| [getStartPointY()](#getStartPointY--) | يحصل على إحداثي Y لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile. |
| [getWidth()](#getWidth--) | يحصل على عرض الـ tile بالبكسل. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الـ tile بالبكسل. |
| [getEndPointX()](#getEndPointX--) | يرجع إحداثي X لأعلى نقطة يمينية في الرسم حيث ينتهي الـ tile. |
| [getEndPointY()](#getEndPointY--) | يرجع إحداثي Y لأعلى نقطة يمينية في الرسم حيث ينتهي الـ tile. |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


يُنشئ مثيلًا جديدًا من فئة Tile.

يقوم هذا المُنشئ بإنشاء كائن tile جديد بالنقطة الابتدائية المحددة والعرض والارتفاع. للحصول على تفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| startPointX | int | إحداثي X لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile. |
| startPointY | int | إحداثي Y لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile. |
| width | int | عرض الـ tile بالبكسل. |
| height | int | ارتفاع الـ tile بالبكسل. |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


يحصل على إحداثي X لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - إحداثي X لأدنى نقطة يسرى.
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


يحصل على إحداثي Y لأدنى نقطة يسرى في الرسم حيث يبدأ الـ tile.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - إحداثي Y لأدنى نقطة يسرى.
### getWidth() {#getWidth--}
```
public final int getWidth()
```


يحصل على عرض الـ tile بالبكسل.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - عرض الـ tile.
### getHeight() {#getHeight--}
```
public final int getHeight()
```


يحصل على ارتفاع الـ tile بالبكسل.

للتفاصيل، راجع [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - ارتفاع الـ tile.
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


يرجع إحداثي X لأعلى نقطة يمينية في الرسم حيث ينتهي الـ tile.

**Returns:**
int - إحداثي X لأعلى نقطة يمينية.
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


يرجع إحداثي Y لأعلى نقطة يمينية في الرسم حيث ينتهي الـ tile.

**Returns:**
int - إحداثي Y للنقطة اليمنى العليا.
