---
title: "VisioRenderingOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "Visio ドキュメントのレンダリングオプションを含みます。"
type: docs
weight: 36
url: /ja/java/com.groupdocs.viewer.options/visiorenderingoptions/
---
**Inheritance:**
java.lang.Object
```
public class VisioRenderingOptions
```

Visio ドキュメントのレンダリングオプションを含みます。


VisioRenderingOptions クラスは、Visio ファイルの処理およびレンダリングのオプションを提供します
GroupDocs.Viewer コンポーネント内です。使用できる設定とパラメーターをカプセル化します
Visio ドキュメントのレンダリングプロセスと出力形式を制御します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/) を参照してください。


使用例:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 VisioRenderingOptions visioRenderingOptions = pngViewOptions.getVisioRenderingOptions();
 visioRenderingOptions.setRenderFiguresOnly(true);

 try (Viewer viewer = new Viewer(visioDocument)) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [VisioRenderingOptions()](#VisioRenderingOptions--) | 新しいインスタンスを初期化します |
VisioRenderingOptions
クラス。
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isRenderFiguresOnly()](#isRenderFiguresOnly--) | 図表を除外し、Visio の図形のみをレンダリングします。 |
|
|  | [setRenderFiguresOnly(boolean renderFiguresOnly)](#setRenderFiguresOnly-boolean-) | 図表を除外し、Visio の図形のみをレンダリングするフラグを設定します。 |
|
|  | [getFigureWidth()](#getFigureWidth--) | 図形の幅を取得します。 |
|
|  | [setFigureWidth(int figureWidth)](#setFigureWidth-int-) | 図形の幅を設定します。 |
|
### VisioRenderingOptions() {#VisioRenderingOptions--}
```
public VisioRenderingOptions()
```


新しいインスタンスを初期化します
VisioRenderingOptions
クラス。


### isRenderFiguresOnly() {#isRenderFiguresOnly--}
```
public boolean isRenderFiguresOnly()
```


図表を除外し、Visio の図形のみをレンダリングします。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes) を参照してください。


**Returns:**
boolean -  true  の場合は Visio の図形のみがレンダリングされ、  false  の場合はそれ以外です。

### setRenderFiguresOnly(boolean renderFiguresOnly) {#setRenderFiguresOnly-boolean-}
```
public void setRenderFiguresOnly(boolean renderFiguresOnly)
```


図表を除外し、Visio の図形のみをレンダリングするフラグを設定します。
詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-visio-documents/#render-only-diagram-shapes) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | renderFiguresOnly | boolean | true  は Visio の図形のみをレンダリングし、 false  は図表を含めます。 |
|

### getFigureWidth() {#getFigureWidth--}
```
public int getFigureWidth()
```


図形の幅を取得します。高さは自動的に計算されます。


**Returns:**
int - 図形の幅です。

### setFigureWidth(int figureWidth) {#setFigureWidth-int-}
```
public void setFigureWidth(int figureWidth)
```


図形の幅を設定します。高さは自動的に計算されます。


***Note:** Default value is 100.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | figureWidth | int | 図形の幅です。 |
|

