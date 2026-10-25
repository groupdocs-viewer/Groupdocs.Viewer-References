---
title: "TextOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "テキストファイルをページに分割するオプションです。"
type: docs
weight: 32
url: /ja/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

テキストファイルをページに分割するオプションです。


TextOptions クラスは、GroupDocs.Viewer コンポーネントでテキストファイルをページに分割するためのオプションを提供します。
テキストファイルがレンダリングおよび表示目的で個々のページに分割される方法を制御できます。


使用例:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | 新しいインスタンスを初期化します |
TextOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | ページ上の行あたりの最大文字数を取得します。 |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | ページ上の行あたりの最大文字数を設定します。 |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | ページあたりの最大行数を取得します。 |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | ページあたりの最大行数を設定します。 |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


新しいインスタンスを初期化します
TextOptions
クラス。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) を参照してください。


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


ページ上の行あたりの最大文字数を取得します。


***Note:** The default value is 85.*
デフォルト値は 85 です。詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) を参照してください。


**Returns:**
int - ページ上の行あたりの最大文字数。

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


ページ上の行あたりの最大文字数を設定します。


***Note:** The default value is 85.*
デフォルト値は 85 です。詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxCharsPerRow | int | ページ上の行あたりの最大文字数。 |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


ページあたりの最大行数を取得します。


***Note:** The default value is 55.*
デフォルト値は 55 です。詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) を参照してください。


**Returns:**
int - 最大行数。

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


ページあたりの最大行数を設定します。


***Note:** The default value is 55.*
デフォルト値は 55 です。詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | maxRowsPerPage | int | 最大行数。 |
|

