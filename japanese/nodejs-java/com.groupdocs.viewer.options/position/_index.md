---
title: "Position"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "透かしの位置を定義します。"
type: docs
weight: 43
url: /ja/nodejs-java/com.groupdocs.viewer.options/position/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum Position extends Enum<Position>
```

透かしの位置を定義します。

Position 列挙型は、GroupDocs.Viewer コンポーネントにおける透かしのさまざまな位置を表します。レンダリング処理中に文書や画像上の透かしの配置を指定するために使用できる、事前定義された位置のセットを提供します。

使用例:

```

 Watermark watermark = new Watermark("Watermark");
 watermark.setPosition(Position.DIAGONAL);
 watermark.setColor(java.awt.Color.GREEN);
 watermark.setSize(Size.HALF_SIZE);

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setWatermark(watermark);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DIAGONAL](#DIAGONAL) | 対角位置。 |
| [TOP_LEFT](#TOP-LEFT) | 左上位置。 |
| [TOP_CENTER](#TOP-CENTER) | 上部中央位置。 |
| [TOP_RIGHT](#TOP-RIGHT) | 右上位置。 |
| [BOTTOM_LEFT](#BOTTOM-LEFT) | 左下位置。 |
| [BOTTOM_CENTER](#BOTTOM-CENTER) | 下部中央位置。 |
| [BOTTOM_RIGHT](#BOTTOM-RIGHT) | 右下位置。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### DIAGONAL {#DIAGONAL}
```
public static final Position DIAGONAL
```


対角位置。この位置は対角線上の配置または配置を表します。

### TOP_LEFT {#TOP-LEFT}
```
public static final Position TOP_LEFT
```


左上位置。この位置は左上隅の配置または配置を表します。

### TOP_CENTER {#TOP-CENTER}
```
public static final Position TOP_CENTER
```


上部中央位置。この位置は上部中央の配置または配置を表します。

### TOP_RIGHT {#TOP-RIGHT}
```
public static final Position TOP_RIGHT
```


右上位置。この位置は右上隅の配置または配置を表します。

### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final Position BOTTOM_LEFT
```


左下位置。この位置は左下隅の配置または配置を表します。

### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final Position BOTTOM_CENTER
```


下部中央位置。この位置は下部中央の配置または配置を表します。

### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final Position BOTTOM_RIGHT
```


右下位置。この位置は右下隅の配置または配置を表します。

### values() {#values--}
```
public static Position[] values()
```




**Returns:**
com.groupdocs.viewer.options.Position[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static Position valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[Position](../../com.groupdocs.viewer.options/position)
