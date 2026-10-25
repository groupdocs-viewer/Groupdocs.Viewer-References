---
title: "WordsPageNumberLocation"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "読み込まれた WordProcessing ドキュメントにページ番号を強制的に適用するかどうか、適用する場合はページ番号の配置場所を制御します。"
type: docs
weight: 48
url: /ja/java/com.groupdocs.viewer.options/wordspagenumberlocation/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum WordsPageNumberLocation extends Enum<WordsPageNumberLocation>
```

読み込まれた WordProcessing 文書にページ番号付与を強制的に適用するかどうか、適用する場合はページ番号の配置場所を制御します。

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [NOT_APPLY](#NOT-APPLY) | 読み込まれた WordProcessing ドキュメントをそのまま保持します。 |
|
|  | [TOP_LEFT](#TOP-LEFT) | ページ番号をページの左上隅に配置します。 |
|
|  | [TOP_CENTER](#TOP-CENTER) | ページ番号をページの上部中央に配置します。 |
|
|  | [TOP_RIGHT](#TOP-RIGHT) | ページ番号をページの右上隅に配置します。 |
|
|  | [BOTTOM_LEFT](#BOTTOM-LEFT) | ページ番号をページの左下隅に配置します。 |
|
|  | [BOTTOM_CENTER](#BOTTOM-CENTER) | ページ番号をページの下部中央に配置します。 |
|
|  | [BOTTOM_RIGHT](#BOTTOM-RIGHT) | ページ番号をページの右下隅に配置してください。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### NOT_APPLY {#NOT-APPLY}
```
public static final WordsPageNumberLocation NOT_APPLY
```


読み込まれた WordProcessing ドキュメントをそのままにしてください。デフォルト値。


### TOP_LEFT {#TOP-LEFT}
```
public static final WordsPageNumberLocation TOP_LEFT
```


ページ番号をページの左上隅に配置します。


### TOP_CENTER {#TOP-CENTER}
```
public static final WordsPageNumberLocation TOP_CENTER
```


ページ番号をページの上部中央に配置します。


### TOP_RIGHT {#TOP-RIGHT}
```
public static final WordsPageNumberLocation TOP_RIGHT
```


ページ番号をページの右上隅に配置します。


### BOTTOM_LEFT {#BOTTOM-LEFT}
```
public static final WordsPageNumberLocation BOTTOM_LEFT
```


ページ番号をページの左下隅に配置します。


### BOTTOM_CENTER {#BOTTOM-CENTER}
```
public static final WordsPageNumberLocation BOTTOM_CENTER
```


ページ番号をページの下部中央に配置します。


### BOTTOM_RIGHT {#BOTTOM-RIGHT}
```
public static final WordsPageNumberLocation BOTTOM_RIGHT
```


ページ番号をページの右下隅に配置してください。


### values() {#values--}
```
public static WordsPageNumberLocation[] values()
```




**Returns:**
com.groupdocs.viewer.options.WordsPageNumberLocation[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static WordsPageNumberLocation valueOf(String name)
```




**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String |  |

**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation)
