---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "GroupDocs.Viewer を介して WordProcessing ドキュメントで使用される置換フォント 1 つのメタデータとバイナリデータをカプセル化します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

GroupDocs.Viewer を介して WordProcessing ドキュメントで使用される置換フォント 1 つのメタデータとバイナリデータをカプセル化します。イミュータブルクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | すべてのフィールドを初期化するコンストラクタ。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 置換フォントのファミリ名を返します（null ではありません）。 |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | 元フォントのファミリ名を返します（null ではありません）。 |
|
|  | [getStyle()](#getStyle--) | 元フォントのスタイルを返します。 |
|
|  | [getContent()](#getContent--) | 置換フォントのバイナリコンテンツを返します（null ではありません）。 |
|
|  | [getFormat()](#getFormat--) | 置換フォントのフォント形式を返します。 |
|
|  | [toString()](#toString--) | この置換フォントを表す文字列を返します："original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 元のファミリ、置換ファミリ、スタイルに基づく等価性。 |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | ユーティリティメソッドを使用して、このフォントを @font-face CSS ルールとしてシリアライズします。 |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


すべてのフィールドを初期化するコンストラクタ。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | 元のフォント名（システムに見つからない） |
|
|  | substitutedFamilyName | java.lang.String | 置き換えられたフォント名（利用可能） |
|
|  | スタイル | com.groupdocs.viewer.fonts.FontStyles | フォントスタイル（Regular、Bold、Italic、BoldItalic） |
|
|  | content | byte[] | 置き換えられたフォントのバイナリコンテンツ（null ではない） |
|
|  | フォーマット | int | フォント形式（TrueType、OpenType、その他） |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


置換フォントのファミリ名を返します（null ではありません）。


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


元フォントのファミリ名を返します（null ではありません）。


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


元フォントのスタイルを返します。


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


置換フォントのバイナリコンテンツを返します（null ではありません）。


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


置換フォントのフォント形式を返します。


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


この置換フォントを表す文字列を返します："original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


元のファミリ、置き換えられたファミリ、スタイルに基づく等価性。C# IEqualityComparer のような HashSet や HashMap で使用するために必要です。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


ユーティリティメソッドを使用して、このフォントを @font-face CSS ルールとしてシリアライズします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | java.io.Writer |  |

