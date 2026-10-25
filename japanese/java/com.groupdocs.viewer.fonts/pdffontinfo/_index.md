---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Viewer インスタンスにロードされた PDF ドキュメントからの 1 つのフォントのメタ情報とバイナリ データをカプセル化します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

PDF ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化し、Viewer インスタンスにロードします。


このフォントはドキュメント コンテンツで使用され、次のいずれかです：

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF フォント抽出で使用される内部コンストラクタです。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | フォント ファミリ名を取得します。 |
|
|  | [getStyle()](#getStyle--) | このフォントのスタイルを取得します。 |
|
|  | [isEmbedded()](#isEmbedded--) | フォントが PDF ドキュメント内に埋め込まれているかどうかを返します。 |
|
|  | [isInstalled()](#isInstalled--) | フォントが OS にインストールされているかどうかを返します。 |
|
|  | [getFormat()](#getFormat--) | フォントのファイル形式を返します。 |
|
|  | [getContent()](#getContent--) | フォントのバイナリ コンテンツを返します。 |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | このフォントを CSS の @font-face ルールとしてシリアライズします。 |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF フォント抽出で使用される内部コンストラクタです。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | familyName | java.lang.String | フォント ファミリ名 |
|
|  | スタイル | com.groupdocs.viewer.fonts.FontStyles | スタイル (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | フォントが PDF に埋め込まれている場合は true |
|
|  | isInstalled | boolean | フォントが OS にインストールされている場合は true |
|
|  | content | byte[] | バイナリフォントデータ（nullable） |
|
|  | フォーマット | int | フォントファイル形式 |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


フォント ファミリ名を取得します。


**Returns:**
java.lang.String - ファミリ名文字列（null または空文字列ではない）

### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


このフォントのスタイルを取得します。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles - フォントスタイル

### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


フォントが PDF ドキュメント内に埋め込まれているかどうかを返します。


**Returns:**
boolean - 埋め込まれている場合は true

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


フォントが OS にインストールされているかどうかを返します。


**Returns:**
boolean - インストールされている場合は true

### getFormat() {#getFormat--}
```
public int getFormat()
```


フォントのファイル形式を返します。


**Returns:**
int - フォント形式列挙型

### getContent() {#getContent--}
```
public byte[] getContent()
```


フォントのバイナリ コンテンツを返します。


**Returns:**
byte[] - バイト配列、利用できない場合は null

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


このフォントを CSS の @font-face ルールとしてシリアライズします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | output | java.io.Writer | CSS が書き込まれる writer |
|

