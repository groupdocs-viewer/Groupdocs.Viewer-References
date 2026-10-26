---
title: "Size"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "透かしのサイズを含みます。"
type: docs
weight: 30
url: /ja/nodejs-java/com.groupdocs.viewer.options/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

透かしのサイズを含みます。

Size クラスは GroupDocs.Viewer コンポーネントにおける透かしのサイズを表します。幅や高さなど、透かしの寸法を指定するオプションを提供します。

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
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Size(byte relativeSize)](#Size-byte-) | Size クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [FULL_SIZE](#FULL-SIZE) | ページに収まる透かしテキストの最大サイズを表します。 |
| [HALF_SIZE](#HALF-SIZE) | ページに収まる透かしテキストの最大サイズの半分を表します。 |
| [ONE_THIRD](#ONE-THIRD) | ページに収まる透かしテキストの最大サイズの3分の1を表します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getRelativeSize()](#getRelativeSize--) | ページ幅に対する透かしテキストサイズをパーセンテージで返します。 |
### Size(byte relativeSize) {#Size-byte-}
```
public Size(byte relativeSize)
```


Size クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| relativeSize | byte | ページサイズに対するパーセンテージでのサイズです。 |

### FULL_SIZE {#FULL-SIZE}
```
public static final Size FULL_SIZE
```


ページに収まる透かしテキストの最大サイズを表します。

### HALF_SIZE {#HALF-SIZE}
```
public static final Size HALF_SIZE
```


ページに収まる透かしテキストの最大サイズの半分を表します。

### ONE_THIRD {#ONE-THIRD}
```
public static final Size ONE_THIRD
```


ページに収まる透かしテキストの最大サイズの3分の1を表します。

### getRelativeSize() {#getRelativeSize--}
```
public final byte getRelativeSize()
```


ページ幅に対する透かしテキストサイズをパーセンテージで返します。

**Returns:**
byte - パーセンテージで表した透かしテキストサイズです。
