---
title: "Watermark"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "テキスト透かしを表します。"
type: docs
weight: 37
url: /ja/nodejs-java/com.groupdocs.viewer.options/watermark/
---
**Inheritance:**
java.lang.Object
```
public class Watermark
```

テキストウォーターマークを表します。詳細については、[documentation][] を参照してください。

Watermark クラスは、GroupDocs.Viewer コンポーネントにおけるテキストウォーターマークを表します。ドキュメントのレンダリング出力にウォーターマークを定義し適用するために使用されます。

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


[documentation]: https://docs.groupdocs.com/viewer/net/add-text-watermark/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [Watermark(String text)](#Watermark-java.lang.String-) | Watermark クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getText()](#getText--) | 透かしテキストを返します。 |
| [getColor()](#getColor--) | 透かしの色を返します。 |
| [getColorAsHex()](#getColorAsHex--) | 透かしの色を16進形式で返します。 |
| [setColor(Color value)](#setColor-java.awt.Color-) | 透かしの色を設定します。 |
| [setColor(String colorName)](#setColor-java.lang.String-) | 透かしの色を設定します。 |
| [getPosition()](#getPosition--) | 透かしの位置を返します。 |
| [setPosition(Position value)](#setPosition-com.groupdocs.viewer.options.Position-) | 透かしの位置を設定します。 |
| [getSize()](#getSize--) | 透かしのサイズを返します。 |
| [setSize(Size value)](#setSize-com.groupdocs.viewer.options.Size-) | 透かしのサイズを設定します。 |
| [getFontName()](#getFontName--) | 透かしに使用されるフォント名を返します。 |
| [setFontName(String value)](#setFontName-java.lang.String-) | 透かしに使用されるフォント名を設定します。 |
### Watermark(String text) {#Watermark-java.lang.String-}
```
public Watermark(String text)
```


Watermark クラスの新しいインスタンスを初期化します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| テキスト | java.lang.String | 透かしテキストです。 |

### getText() {#getText--}
```
public final String getText()
```


透かしテキストを返します。このメソッドはドキュメントに適用された透かしのテキストを取得します。

**Returns:**
java.lang.String - 透かしテキスト。
### getColor() {#getColor--}
```
public final Color getColor()
```


透かしの色を返します。このメソッドはドキュメントに適用された透かしの色を取得します。

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.awt.Color - 透かしの色。
### getColorAsHex() {#getColorAsHex--}
```
public final String getColorAsHex()
```


透かしの色を16進形式で返します。このメソッドはドキュメントに適用された透かしの色を取得します。

***Note:** The default value is the red color obtained from Color\#getRed().getRed().*

**Returns:**
java.lang.String - 透かしの色（16進形式）。
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


透かしの色を設定します。このメソッドはドキュメントに適用された透かしの色を設定します。

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.awt.Color | 設定する透かしの色です。 |

### setColor(String colorName) {#setColor-java.lang.String-}
```
public final void setColor(String colorName)
```


透かしの色を設定します。このメソッドはドキュメントに適用された透かしの色を設定します。

***Note:** The default value is obtained from Color\#getRed().getRed().*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| colorName | java.lang.String | 設定する透かしの色です。 |

### getPosition() {#getPosition--}
```
public final Position getPosition()
```


透かしの位置を返します。このメソッドはドキュメントに適用された透かしの位置を返します。

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Returns:**
[Position](../../com.groupdocs.viewer.options/position) - the watermark position.
### setPosition(Position value) {#setPosition-com.groupdocs.viewer.options.Position-}
```
public final void setPosition(Position value)
```


透かしの位置を設定します。このメソッドはドキュメントに適用された透かしの位置を設定します。

***Note:** The default value is [Position.DIAGONAL](../../com.groupdocs.viewer.options/position\#DIAGONAL).*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Position](../../com.groupdocs.viewer.options/position) | 透かしの位置です。 |

### getSize() {#getSize--}
```
public final Size getSize()
```


透かしのサイズを返します。このメソッドはドキュメントに適用された透かしのサイズを取得します。

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Returns:**
[Size](../../com.groupdocs.viewer.options/size) - the watermark size.
### setSize(Size value) {#setSize-com.groupdocs.viewer.options.Size-}
```
public final void setSize(Size value)
```


透かしのサイズを設定します。このメソッドは、ドキュメントに適用される透かしのサイズを設定します。

***Note:** The default value is [Size.FULL\_SIZE](../../com.groupdocs.viewer.options/size\#FULL-SIZE).*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.groupdocs.viewer.options/size) | 透かしのサイズ。 |

### getFontName() {#getFontName--}
```
public final String getFontName()
```


透かしに使用されるフォント名を返します。

**Returns:**
java.lang.String - 透かしに使用されるフォント名。
### setFontName(String value) {#setFontName-java.lang.String-}
```
public final void setFontName(String value)
```


透かしに使用されるフォント名を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 透かしに使用されるフォント名。 |

