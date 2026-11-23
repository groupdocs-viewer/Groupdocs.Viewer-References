---
title: "VisioRenderingOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "Visio ドキュメントのレンダリングオプションを含みます。"
type: docs
weight: 36
url: /ja/nodejs-java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio ドキュメントのレンダリングオプションを含みます。

VisioRenderingOptions クラスは、GroupDocs.Viewer コンポーネントで Visio ファイルを処理およびレンダリングするためのオプションを提供します。Visio ドキュメントのレンダリングプロセスと出力形式を制御できる設定やパラメータをカプセル化しています。詳細については、[documentation][] を参照してください。

使用例:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [VisioRenderingOptions()](#VisioRenderingOptions--) | VisioRenderingOptions クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isRenderFiguresOnly()](#isRenderFiguresOnly--) | 図面を除き、Visio の図形のみをレンダリングします。 |
| [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | 図面を除き、Visio の図形のみをレンダリングするフラグを設定します。 |
| [getFigureWidth()](#getFigureWidth--) | 図形の幅を取得します。 |
| [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | 図形の幅を設定します。 |
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


VisioRenderingOptions クラスの新しいインスタンスを初期化します。

### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


図面を除き、Visio の図形のみをレンダリングします。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Returns:**
boolean -  true  の場合は Visio 図のみをレンダリングし、  false  の場合はそれ以外です。
### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


図面を除き、Visio の図形のみをレンダリングするフラグを設定します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderFiguresOnly | boolean | true  は Visio 図のみをレンダリングし、  false  は図全体を含めます。 |

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


図の幅を取得します。高さは自動的に計算されます。

**Returns:**
int - 図の幅です。
### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


図の幅を設定します。高さは自動的に計算されます。

***Note:** Default value is 100.*

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| figureWidth | int | 図の幅です。 |

