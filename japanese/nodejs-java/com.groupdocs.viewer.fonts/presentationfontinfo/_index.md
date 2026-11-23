---
title: "PresentationFontInfo"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Viewer インスタンスにロードされた Presentation ドキュメントで使用されるフォントのメタデータとバイナリ データをカプセル化します。"
type: docs
weight: 15
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Viewer インスタンスにロードされた Presentation ドキュメントで使用されるフォントのメタデータとバイナリ データをカプセル化します。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれるか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされることがあります。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | フォントファミリ名を取得します（null または空になることはありません）。 |
| [getStyle()](#getStyle--) | フォントのスタイルを取得します：Regular、Bold、Italic、または BoldItalic。 |
| [isEmbedded()](#isEmbedded--) | このフォントが Viewer インスタンスに読み込まれたドキュメント内に埋め込まれているかどうかを示します。 |
| [getFormat()](#getFormat--) | フォント形式を取得します（TrueType、OpenType など）。 |
| [getContent()](#getContent--) | バイナリフォントコンテンツを取得します。フォントデータが利用できない場合は null が返されます。 |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | 指定された writer を使用して、このフォント情報を CSS の @font-face ルールにシリアライズします。 |
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


フォントファミリ名を取得します（null または空になることはありません）。

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


フォントのスタイルを取得します：Regular、Bold、Italic、または BoldItalic。

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


このフォントが Viewer インスタンスに読み込まれたドキュメント内に埋め込まれているかどうかを示します。注：スプレッドシートドキュメントは埋め込みフォントを含めることができないため、常に false が返されます。

**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


フォント形式を取得します（TrueType、OpenType など）。メタデータのみが利用可能な場合は FontFormat.Unknown を返します。

**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


バイナリフォントコンテンツを取得します。フォントデータが利用できない場合は null が返されます。

**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


指定された writer を使用して、このフォント情報を CSS の @font-face ルールにシリアライズします。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 出力 | java.io.Writer | CSS を書き込む writer（null であってはなりません） |

