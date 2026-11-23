---
title: "Tile"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "描画領域を表します。"
type: docs
weight: 33
url: /ja/nodejs-java/com.groupdocs.viewer.options/tile/
---
**Inheritance:**
java.lang.Object
```
public class Tile
```

描画領域を表します。

Tile クラスは GroupDocs.Viewer コンポーネント内の描画領域を表します。これは、ドキュメント内で別々にレンダリングまたは処理する必要がある特定の領域やエリアを定義するために使用されます。詳細については、[documentation][].

使用例:

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
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Tile(int startPointX, int startPointY, int width, int height)](#Tile-int-int-int-int-) | Tile クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getStartPointX()](#getStartPointX--) | タイルが開始する描画上の左下点の X 座標を取得します。 |
| [getStartPointY()](#getStartPointY--) | タイルが開始する描画上の左下点の Y 座標を取得します。 |
| [getWidth()](#getWidth--) | タイルの幅（ピクセル単位）を取得します。 |
| [getHeight()](#getHeight--) | タイルの高さ（ピクセル単位）を取得します。 |
| [getEndPointX()](#getEndPointX--) | タイルが終了する描画上の右上点の X 座標を返します。 |
| [getEndPointY()](#getEndPointY--) | タイルが終了する描画上の右上点の Y 座標を返します。 |
### Tile(int startPointX, int startPointY, int width, int height) {#Tile-int-int-int-int-}
```
public Tile(int startPointX, int startPointY, int width, int height)
```


Tile クラスの新しいインスタンスを初期化します。

このコンストラクタは、指定された開始点、幅、および高さを持つ新しいタイルオブジェクトを作成します。詳細については、[documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startPointX | int | タイルが開始する描画上の左下点の X 座標。 |
| startPointY | int | タイルが開始する描画上の左下点の Y 座標。 |
| width | int | タイルの幅（ピクセル単位）。 |
| height | int | タイルの高さ（ピクセル単位）。 |

### getStartPointX() {#getStartPointX--}
```
public final int getStartPointX()
```


タイルが開始する描画上の左下点の X 座標を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 左下点の X 座標。
### getStartPointY() {#getStartPointY--}
```
public final int getStartPointY()
```


タイルが開始する描画上の左下点の Y 座標を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - 左下点の Y 座標。
### getWidth() {#getWidth--}
```
public final int getWidth()
```


タイルの幅（ピクセル単位）を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - タイルの幅。
### getHeight() {#getHeight--}
```
public final int getHeight()
```


タイルの高さ（ピクセル単位）を取得します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#split-a-drawing-into-tiles

**Returns:**
int - タイルの高さ。
### getEndPointX() {#getEndPointX--}
```
public final int getEndPointX()
```


タイルが終了する描画上の右上点の X 座標を返します。

**Returns:**
int - 右上点の X 座標。
### getEndPointY() {#getEndPointY--}
```
public final int getEndPointY()
```


タイルが終了する描画上の右上点の Y 座標を返します。

**Returns:**
int - 最高右点の Y 座標です。
