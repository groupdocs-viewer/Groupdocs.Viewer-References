---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Viewer インスタンスにロードされた Spreadsheet ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer インスタンスにロードされた Spreadsheet ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化します。Spreadsheet ドキュメントは埋め込みフォントを持つことができないため、Viewer.getAllFonts() メソッドで返されるこの特定のフォントは、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
|
|  | [getStyle()](#getStyle--) | このフォントのスタイル \\u2014 Regular、Bold、Italic、または BoldItalic のいずれかです。 |
|
|  | [isStrikeout()](#isStrikeout--) | フォントが単一の取り消し線かどうかを示します。 |
|
|  | [isUnderline()](#isUnderline--) | フォントに下線があるかどうかを示します。 |
|
|  | [getColor()](#getColor--) | このフォントの色。 |
|
|  | [getCharset()](#getCharset--) | このフォントの文字セットです。 |
|
|  | [getContent()](#getContent--) | このフォントのコンテンツをバイト配列として取得します。 |
|
|  | [getFormat()](#getFormat--) | このフォントの形式です。 |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | このフォント情報を @font-face の at-rule としてシリアライズし、指定された writer に書き込みます。 |
|
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


このフォントのスタイル \\u2014 Regular、Bold、Italic、または BoldItalic のいずれかです。


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


このフォントの色。


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
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


このフォントの内容をバイト配列として取得します。メタ情報のみが利用可能な場合、null になることがあります。


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


このフォント情報を @font-face の at-rule としてシリアライズし、指定された writer に書き込みます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | output | java.io.Writer | シリアライズされたテキストデータを書き込むデバイス。 |
|

