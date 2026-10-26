---
title: "FontFormat"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "UsedFontInfo クラスに存在し得るすべてのフォント形式を表します。"
type: docs
weight: 11
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/fontformat/
---
**Inheritance:**
java.lang.Object
```
public final class FontFormat
```

UsedFontInfo クラスに存在する可能性のあるすべてのフォント形式を表します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Unknown](#Unknown) | 不明または無効なフォント形式です。 |
| [TrueType](#TrueType) | TrueType フォント形式（TTF）。 |
| [OpenType](#OpenType) | OpenType フォント形式（OTF）。 |
| [TrueTypeCollection](#TrueTypeCollection) | TrueType Collection フォント形式 (TTC)。 |
| [EmbeddedOpenType](#EmbeddedOpenType) | Embedded OpenType フォント形式 (EOT)。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [toString(int format)](#toString-int-) | 形式の値を人間が読みやすい文字列に変換します。 |
### Unknown {#Unknown}
```
public static final int Unknown
```


不明または無効なフォント形式です。

### TrueType {#TrueType}
```
public static final int TrueType
```


TrueType フォント形式（TTF）。

### OpenType {#OpenType}
```
public static final int OpenType
```


OpenType フォント形式（OTF）。

### TrueTypeCollection {#TrueTypeCollection}
```
public static final int TrueTypeCollection
```


TrueType Collection フォント形式 (TTC)。

### EmbeddedOpenType {#EmbeddedOpenType}
```
public static final int EmbeddedOpenType
```


Embedded OpenType フォント形式 (EOT)。

### toString(int format) {#toString-int-}
```
public static String toString(int format)
```


形式の値を人間が読みやすい文字列に変換します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| フォーマット | int | フォント形式の値 |

**Returns:**
java.lang.String - フォント形式の文字列表現
