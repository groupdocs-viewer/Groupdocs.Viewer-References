---
title: "KnownColors"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: 
type: docs
weight: 10
url: /ja/java/com.groupdocs.viewer.drawing.rgb24color/knowncolors/
---
**Inheritance:**
java.lang.Object
```
public class KnownColors
```
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [tryFindColor(String keyword, Rgb24Color[] output)](#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---) | 文字列名で色を検索しようとします。 |
|
|  | [tryFindName(Rgb24Color color, String[] name)](#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---) | RGB 値で色名を検索しようとします。 |
|
### tryFindColor(String keyword, Rgb24Color[] output) {#tryFindColor-java.lang.String-com.groupdocs.viewer.drawing.Rgb24Color---}
```
public static boolean tryFindColor(String keyword, Rgb24Color[] output)
```


文字列名で色を検索しようとします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | キーワード | java.lang.String | 色名です。 |
|
|  | output | [Rgb24Color\[\]](../../com.groupdocs.viewer.drawing/rgb24color) | 見つかった色の結果コンテナ、失敗した場合は CssLevel1.Black です。 |
|

**Returns:**
boolean - 名前で色が正常に見つかった場合は True、そうでない場合は false です。

### tryFindName(Rgb24Color color, String[] name) {#tryFindName-com.groupdocs.viewer.drawing.Rgb24Color-java.lang.String---}
```
public static boolean tryFindName(Rgb24Color color, String[] name)
```


RGB 値で色名を検索しようとします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | color | [Rgb24Color](../../com.groupdocs.viewer.drawing/rgb24color) | カラーインスタンス。 |
|
|  | 名前 | java.lang.String[] | 見つかったカラー名の結果コンテナ、失敗した場合は null。 |
|

**Returns:**
boolean - 与えられたカラーで名前が正常に見つかった場合は true、そうでない場合は false。

