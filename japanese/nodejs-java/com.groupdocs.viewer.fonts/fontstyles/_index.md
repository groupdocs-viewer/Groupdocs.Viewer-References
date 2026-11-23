---
title: "FontStyles"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "ドキュメントで使用されるフォントの4つの可能なスタイル（Regular、Bold、Italic、Bold Italic）を表します。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

ドキュメントで使用されるフォントの 4 つの可能なスタイル（Regular、Bold、Italic、Bold Italic）を表します。
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | bold/italic フラグから FontStyles インスタンスを作成します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [toString(int style)](#toString-int-) | スタイルの値を人間が読みやすい文字列に変換します。 |
| [getName()](#getName--) | このフォントスタイルの読みやすい名前を返します。 |
| [isBold()](#isBold--) | bold ビットが設定されている場合に true を返します。 |
| [isItalic()](#isItalic--) | italic ビットが設定されている場合に true を返します。 |
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Union (C\# 演算子 +) |
| [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Difference (C\# 演算子 -) |
| [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | フォントスタイル名を FontStyles に解析します。 |
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


bold/italic フラグから FontStyles インスタンスを作成します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


スタイルの値を人間が読みやすい文字列に変換します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スタイル | int | フォントスタイルの値 |

**Returns:**
java.lang.String - フォントスタイルの文字列表現
### getName() {#getName--}
```
public String getName()
```


このフォントスタイルの読みやすい名前を返します。

**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


bold ビットが設定されている場合に true を返します。

**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


italic ビットが設定されている場合に true を返します。

**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


Union (C\# 演算子 +)

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| first | com.groupdocs.viewer.fonts.FontStyles |  |
| second | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Difference (C\# 演算子 -)

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 被減数 | com.groupdocs.viewer.fonts.FontStyles |  |
| 減数 | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


フォントスタイル名を FontStyles に解析します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スタイル | java.lang.String |  |
| 解析済み | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - 成功した場合は true、そうでない場合は false。
