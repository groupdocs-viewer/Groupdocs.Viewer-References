---
title: "ページ"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "表示可能な単一ページを表します。"
type: docs
weight: 21
url: /ja/nodejs-java/com.groupdocs.viewer.results/page/
---
**All Implemented Interfaces:**
java.io.Serializable
```
public interface Page extends Serializable
```

表示可能な単一ページを表します。

Page インターフェイスは、GroupDocs.Viewer コンポーネントで表示できる単一ページにアクセスし操作するための契約を定義します。ページ番号、サイズ、その他のプロパティなどの情報を取得するメソッドを提供します。

使用例:

```

 try (Viewer viewer = new Viewer("document.pst")) {
     final OutlookViewInfo viewInfo = (OutlookViewInfo) viewer.getViewInfo(ViewInfoOptions.forHtmlView());
     List pages = viewInfo.getPages();
     for (Page page : pages) {
         // Use the page object for further operations
     }
 }
 
```

***Note:** The default implementation of this interface is PageImpl.*
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | ワークシートまたはページの名前を取得します。 |
| [setName(String name)](#setName-java.lang.String-) | ワークシートまたはページの名前を設定します。 |
| [getNumber()](#getNumber--) | ページ番号を取得します。 |
| [setNumber(int number)](#setNumber-int-) | ページ番号を設定します。 |
| [isVisible()](#isVisible--) | ページの表示状態インジケーターを取得します。 |
| [setVisible(boolean visible)](#setVisible-boolean-) | ページの表示状態インジケーターを設定します。 |
| [getWidth()](#getWidth--) | JPG または PNG として表示する際のページ幅（ピクセル）を取得します。 |
| [setWidth(int width)](#setWidth-int-) | JPG または PNG として表示する際のページ幅（ピクセル）を設定します。 |
| [getHeight()](#getHeight--) | JPG または PNG として表示する際のページ高さ（ピクセル）を取得します。 |
| [setHeight(int height)](#setHeight-int-) | JPG または PNG として表示する際のページ高さ（ピクセル）を設定します。 |
| [getLines()](#getLines--) | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を取得します。 |
| [setLines(List<Line> lines)](#setLines-java.util.List-com.groupdocs.viewer.results.Line--) | テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を設定します。 |
### getName() {#getName--}
```
public abstract String getName()
```


ワークシートまたはページの名前を取得します。

**Returns:**
java.lang.String - ワークシートまたはページの名前です。
### setName(String name) {#setName-java.lang.String-}
```
public abstract void setName(String name)
```


ワークシートまたはページの名前を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 名前 | java.lang.String | ワークシートまたはページに設定する名前です。 |

### getNumber() {#getNumber--}
```
public abstract int getNumber()
```


ページ番号を取得します。

**Returns:**
int - ページ番号です。
### setNumber(int number) {#setNumber-int-}
```
public abstract void setNumber(int number)
```


ページ番号を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 番号 | int | 設定するページ番号です。 |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


ページの表示状態インジケーターを取得します。

**Returns:**
boolean - ページの表示状態インジケーターです。
### setVisible(boolean visible) {#setVisible-boolean-}
```
public abstract void setVisible(boolean visible)
```


ページの表示状態インジケーターを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| visible | boolean | ページが表示されている場合は true、そうでない場合は false。 |

### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


JPG または PNG として表示する際のページ幅（ピクセル）を取得します。

**Returns:**
int - ページの幅。
### setWidth(int width) {#setWidth-int-}
```
public abstract void setWidth(int width)
```


JPG または PNG として表示する際のページ幅（ピクセル）を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | ページに設定する幅。 |

### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


JPG または PNG として表示する際のページ高さ（ピクセル）を取得します。

**Returns:**
int - ページの高さ。
### setHeight(int height) {#setHeight-int-}
```
public abstract void setHeight(int height)
```


JPG または PNG として表示する際のページ高さ（ピクセル）を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| height | int | ページに設定する高さ。 |

### getLines() {#getLines--}
```
public abstract List<Line> getLines()
```


テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を取得します。

**Returns:**
java.util.List<com.groupdocs.viewer.results.Line> - ページに含まれる行のリスト。
### setLines(List<Line> lines) {#setLines-java.util.List-com.groupdocs.viewer.results.Line--}
```
public abstract void setLines(List<Line> lines)
```


テキスト抽出が有効な状態で JPG または PNG として表示する際のページに含まれる行を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| 行 | java.util.List<com.groupdocs.viewer.results.Line> | ページに設定する行のリスト。 |

