---
title: "SpreadsheetFontInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Viewer インスタンスに読み込まれたスプレッドシートドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化します。"
type: docs
weight: 16
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer インスタンスに読み込まれたスプレッドシートドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化します。スプレッドシートドキュメントは埋め込みフォントを持つことができないため、Viewer.getAllFonts() メソッドで返されるこの特定のフォントは、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされます。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
| [getStyle()](#getStyle--) | このフォントのスタイル \\u2014 は Regular、Bold、Italic、または BoldItalic です。 |
| [isStrikeout()](#isStrikeout--) | フォントが単一の取り消し線かどうかを示します。 |
| [isUnderline()](#isUnderline--) | フォントに下線があるかどうかを示します。 |
| [getColor()](#getColor--) | このフォントの色です。 |
| [getCharset()](#getCharset--) | このフォントの文字セットです。 |
| [getContent()](#getContent--) | このフォントの内容をバイト配列として取得します。 |
| [getFormat()](#getFormat--) | このフォントの形式です。 |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | このフォント情報を @font-face at-rule としてシリアライズし、指定された writer に書き込みます。 |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


このフォントのスタイル \\u2014 は Regular、Bold、Italic、または BoldItalic です。

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


フォントが単一の取り消し線かどうかを示します。

**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


フォントに下線があるかどうかを示します。

**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


このフォントの色です。

**Returns:**
com.groupdocs.viewer.drawing.Argb32Color
### getCharset() {#getCharset--}
```
public int getCharset()
```


このフォントの文字セットです。

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


このフォントの内容をバイト配列として取得します。メタ情報のみが利用可能な場合は null になることがあります。

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


このフォントの形式です。

**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


このフォント情報を @font-face at-rule としてシリアライズし、指定された writer に書き込みます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 出力 | java.io.Writer | シリアライズされたテキストデータを書き込むデバイスです。 |

