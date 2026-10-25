---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Viewer インスタンスにロードされた WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Viewer インスタンスにロードされた WordProcessing ドキュメントからのフォント 1 つのメタ情報とバイナリ データをカプセル化します。このフォントはドキュメントの内容で使用され、ドキュメント自体に埋め込まれているか、GroupDocs.Viewer が実行されているオペレーティングシステムにインストールされています。

不変クラスです。そのインスタンスは GroupDocs.Viewer によって生成され、返されます。
public API であり、通常はユーザーが作成すべきではありません。
詳細については、ドキュメントをご覧ください:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。 |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | フォントの代替ファミリ名です。 |
|
|  | [getStyle()](#getStyle--) | フォントのスタイル \u2014 Regular、Bold、Italic、または BoldItalic のいずれかです。 |
|
|  | [isEmbedded()](#isEmbedded--) | このフォントがドキュメントに埋め込まれているか (true)、システムフォントか (false) を示します。 |
|
|  | [getFormat()](#getFormat--) | このフォントの形式です。 |
|
|  | [getContent()](#getContent--) | このフォントの内容をバイト配列として、利用できない場合は null です。 |
|
|  | [getCharset()](#getCharset--) | このフォントの文字セットです。 |
|
|  | [toString()](#toString--) | このフォントに関するデバッグ情報を次のテンプレートで返します: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | このフォント情報を @font-face CSS ルールとしてシリアライズし、指定された writer に書き込みます。 |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


スタイルなしのフォントのファミリ名で、null または空文字列になることはありません。


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


フォントの代替ファミリ名です。存在しない場合は空文字列を返します。


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


フォントのスタイル \u2014 Regular、Bold、Italic、または BoldItalic のいずれかです。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


このフォントがドキュメントに埋め込まれているか (true)、システムフォントか (false) を示します。


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


このフォントの形式です。メタ情報のみでバイナリコンテンツが欠如している場合、FontFormat.UNKNOWN を返すことがあります。


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


このフォントの内容をバイト配列として、利用できない場合は null です。


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


このフォントの文字セットです。


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


このフォントに関するデバッグ情報を次のテンプレートで返します: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


このフォント情報を @font-face CSS ルールとしてシリアライズし、指定された writer に書き込みます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | output | java.io.Writer | シリアライズされた CSS を受け取る writer。 |
|

