---
title: "TextOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "テキストファイルのページ分割オプションです。"
type: docs
weight: 32
url: /ja/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

テキストファイルのページ分割オプションです。

TextOptions クラスは GroupDocs.Viewer コンポーネントでテキストファイルをページに分割するためのオプションを提供します。テキストファイルが個々のページに分割され、レンダリングおよび表示される方法を制御できます。

使用例:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [TextOptions()](#TextOptions--) | TextOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | ページ上の行あたりの最大文字数を取得します。 |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | ページ上の行あたりの最大文字数を設定します。 |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | ページあたりの最大行数を取得します。 |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | ページあたりの最大行数を設定します。 |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


TextOptions クラスの新しいインスタンスを初期化します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


ページ上の行あたりの最大文字数を取得します。

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - ページ上の行あたりの最大文字数。
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


ページ上の行あたりの最大文字数を設定します。

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxCharsPerRow | int | ページ上の行あたりの最大文字数。 |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


ページあたりの最大行数を取得します。

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - 最大行数。
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


ページあたりの最大行数を設定します。

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| maxRowsPerPage | int | 最大行数。 |

