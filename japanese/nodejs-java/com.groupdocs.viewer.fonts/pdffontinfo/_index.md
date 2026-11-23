---
title: "PdfFontInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Viewer インスタンスにロードされた PDF ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。"
type: docs
weight: 14
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

PDF ドキュメントからのフォント 1 つのメタ情報とバイナリデータをカプセル化し、Viewer インスタンスにロードします。

このフォントはドキュメントのコンテンツで使用され、次のいずれかです：

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF フォント抽出で使用される内部コンストラクタです。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | フォントファミリー名を取得します。 |
| [getStyle()](#getStyle--) | このフォントのスタイルを取得します。 |
| [isEmbedded()](#isEmbedded--) | フォントが PDF ドキュメントに埋め込まれているかどうかを返します。 |
| [isInstalled()](#isInstalled--) | フォントが OS にインストールされているかどうかを返します。 |
| [getFormat()](#getFormat--) | フォントのファイル形式を返します。 |
| [getContent()](#getContent--) | フォントのバイナリ コンテンツを返します。 |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | このフォントを CSS の @font-face ルールとしてシリアライズします。 |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF フォント抽出で使用される内部コンストラクタです。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| familyName | java.lang.String | フォント ファミリー名 |
| スタイル | com.groupdocs.viewer.fonts.FontStyles | スタイル (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | フォントが PDF に埋め込まれている場合は true |
| isInstalled | boolean | フォントが OS にインストールされている場合は true |
| コンテンツ | byte[] | バイナリフォントデータ（nullable） |
| フォーマット | int | フォントファイルフォーマット |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


フォントファミリー名を取得します。

**Returns:**
java.lang.String - ファミリ名文字列（nullまたは空ではない）
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


フォントが PDF ドキュメントに埋め込まれているかどうかを返します。

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
int - フォントフォーマット列挙型
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
| 出力 | java.io.Writer | CSS が書き込まれる writer |

