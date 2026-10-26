---
title: "Tile"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "表示绘图区域。"
type: docs
weight: 33
url: /zh/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

表示绘图区域。

Tile 类表示 GroupDocs.Viewer 组件中的绘图区域。它用于定义文档中需要单独渲染或处理的特定区域或区域。有关详细信息，请参阅 [documentation][].

示例用法：

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
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | 初始化 Tile 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | 获取瓦片开始处绘图左下点的 X 坐标。 |
| [getStartPointY()](#getStartPointY--) | 获取瓦片开始处绘图左下点的 Y 坐标。 |
| [getWidth()](#getWidth--) | 获取瓦片的像素宽度。 |
| [getHeight()](#getHeight--) | 获取瓦片的像素高度。 |
| [getEndPointX()](#getEndPointX--) | 返回瓦片结束处绘图右上点的 X 坐标。 |
| [getEndPointY()](#getEndPointY--) | 返回瓦片结束处绘图右上点的 Y 坐标。 |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


初始化 Tile 类的新实例。

此构造函数使用指定的起始点、宽度和高度创建一个新的瓦片对象。有关详细信息，请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| startPointX | int | 瓦片开始处绘图左下点的 X 坐标。 |
| startPointY | int | 瓦片开始处绘图左下点的 Y 坐标。 |
| width | int | 瓦片的像素宽度。 |
| height | int | 瓦片的像素高度。 |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


获取瓦片开始处绘图左下点的 X 坐标。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 左下点的 X 坐标。
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


获取瓦片开始处绘图左下点的 Y 坐标。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 左下点的 Y 坐标。
### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取瓦片的像素宽度。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 瓦片的宽度。
### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取瓦片的像素高度。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 瓦片的高度。
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


返回瓦片结束处绘图右上点的 X 坐标。

**Returns:**
int - 右上点的 X 坐标。
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


返回瓦片结束处绘图右上点的 Y 坐标。

**Returns:**
int - 最高右侧点的 Y 坐标。
