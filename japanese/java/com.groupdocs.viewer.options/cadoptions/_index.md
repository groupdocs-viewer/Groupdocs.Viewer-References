---
title: "CadOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "CAD 図面のレンダリングオプションを提供します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD 図面のレンダリングオプションを提供します。


CadOptions クラスは、使用できるさまざまな設定とパラメータをカプセル化します
GroupDocs.Viewer コンポーネントで CAD 図面のレンダリングを制御するためです。


詳細情報とコード例については、[Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) と [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/) を参照してください。


使用例:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## フィールド

| フィールド | 説明 |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | プロッタに関連付けられた PC3 (Plotter Configuration) ファイルを取得します。 |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | プロッタに関連付けられた PC3 (Plotter Configuration) ファイルを設定します。 |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | 新しいインスタンスを初期化します |
CadOptions
スケール係数でレンダリングするためのクラスです。
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | 新しいインスタンスを初期化します |
CadOptions
幅でレンダリングするためのクラスです。
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | 新しいインスタンスを初期化します |
CadOptions
高さでレンダリングするためのクラスです。
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | 新しいインスタンスを初期化します |
CadOptions
幅と高さでレンダリングするためのクラスです。
|
|  | [getScaleFactor()](#getScaleFactor--) | レンダリングのスケール係数を取得します。 |
|
|  | [getWidth()](#getWidth--) | 出力結果の幅（ピクセル）を取得します。 |
|
|  | [getHeight()](#getHeight--) | 出力結果の高さ（ピクセル）を取得します。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 画像の背景色を取得します。 |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | 画像の背景色を取得します。 |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | 画像の背景色を設定します。 |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | 画像の背景色を設定します。 |
|
|  | [getTiles()](#getTiles--) | レンダリングする描画領域を取得します。 |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | レンダリングする描画領域を設定します。 |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | CAD ドキュメントのレイアウトをレンダリングするかどうかを示します。 |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | CAD ドキュメントのレイアウトをレンダリングするかどうかを設定します。 |
|
|  | [getLayoutName()](#getLayoutName--) | レンダリングする特定のレイアウトの名前を取得します。 |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | レンダリングする特定のレイアウトの名前を設定します。 |
|
|  | [getLayers()](#getLayers--) | レンダリングする CAD 図面レイヤーを取得します。 |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | レンダリングする CAD 図面レイヤーを取得します。 |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | このフラグを true に設定すると、CAD ファミリ内のすべての形式に対して、パフォーマンス重視の特別な変換モードが有効になります。 |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | このフラグを true に設定すると、CAD ファミリ内のすべての形式に対して、パフォーマンス重視の特別な変換モードが有効になります。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | この CadOptions オブジェクトが別のオブジェクトと等しいかどうかをチェックします。 |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


プロッタに関連付けられた PC3 (Plotter Configuration) ファイルを取得します。


**Returns:**
java.lang.String - PC3 ファイルのパス。

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


プロッタに関連付けられた PC3 (Plotter Configuration) ファイルを設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pc3File | java.lang.String | PC3 ファイルのパスです。 |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


新しいインスタンスを初期化します
CadOptions
スケール係数でレンダリングするためのクラスです。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | scaleFactor | double | レンダリングのスケールファクタです。1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


新しいインスタンスを初期化します
CadOptions
幅でレンダリングするためのクラスです。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | width | int | 出力結果の幅（ピクセル）です。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


新しいインスタンスを初期化します
CadOptions
高さでレンダリングするためのクラスです。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | height | int | 出力結果の高さ（ピクセル）です。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


新しいインスタンスを初期化します
CadOptions
幅と高さでレンダリングするためのクラスです。


コード例については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | width | int | 出力結果の幅（ピクセル）です。 |
|
|  | height | int | 出力結果の高さ（ピクセル）です。 |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


レンダリングのスケール係数を取得します。
1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。


**Returns:**
double - レンダリングのスケールファクタです。

### getWidth() {#getWidth--}
```
public final int getWidth()
```


出力結果の幅（ピクセル）を取得します。


**Returns:**
int - 出力結果の幅です。

### getHeight() {#getHeight--}
```
public final int getHeight()
```


出力結果の高さ（ピクセル）を取得します。


**Returns:**
int - 出力結果の高さです。

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


画像の背景色を取得します。


**Returns:**
java.awt.Color - 画像の背景色です。

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


画像の背景色を取得します。


**Returns:**
java.lang.String - 0xFFFFFF 形式の画像背景色です。

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


画像の背景色を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | 画像の背景色です。 |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


画像の背景色を設定します。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | colorName | java.lang.String | 画像の背景色名です。 |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


レンダリングする描画領域を取得します。
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
この
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
および
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) オプションは無視されます
タイルでレンダリングする場合.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - 描画領域のリストです。

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


レンダリングする描画領域を設定します。
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
この
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
および
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) オプションは無視されます
タイルでレンダリングする場合.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.options.Tile> | 描画領域のリストです。 |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


CAD ドキュメントのレイアウトをレンダリングするかどうかを示します。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
デフォルトでは、Model のみがレンダリングされます。*


**Returns:**
boolean -  true  レイアウトをレンダリングすべき場合、  false  それ以外の場合。

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


CAD ドキュメントのレイアウトをレンダリングするかどうかを設定します。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
デフォルトでは、Model のみがレンダリングされます。*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | boolean | true  レイアウトをレンダリングする場合、  false  それ以外の場合。 |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


特定のレイアウトをレンダリングする名前を取得します。レイアウト名は大文字小文字を区別します。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
デフォルトでは、Model のみがレンダリングされます。*


**Returns:**
java.lang.String - 特定のレイアウトをレンダリングする名前です。

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


特定のレイアウトをレンダリングする名前を設定します。レイアウト名は大文字小文字を区別します。
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
デフォルトでは、Model のみがレンダリングされます。*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.lang.String | 特定のレイアウトをレンダリングする名前です。 |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


レンダリングする CAD 図面レイヤーを取得します。


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 描画レイヤーです。

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


レンダリングする CAD 図面レイヤーを取得します。
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 描画レイヤーです。 |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


このフラグを true に設定すると、CAD ファミリ内のすべての形式に対して、特別なパフォーマンス指向の変換モードが有効になります。このモードでは、変換速度が大幅に速くなりますが、生成されるドキュメントの品質は著しく低下します。デフォルトでは、無効 (false) です。生成されるドキュメントの品質は、パフォーマンスを犠牲にして可能な限り最高になります。


**Returns:**
boolean -  true  パフォーマンス指向の変換モードが有効な場合、  false  それ以外の場合。

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


このフラグを true に設定すると、CAD ファミリ内のすべての形式に対して、特別なパフォーマンス指向の変換モードが有効になります。このモードでは、変換速度が大幅に速くなりますが、生成されるドキュメントの品質は著しく低下します。デフォルトでは、無効 (false) です。生成されるドキュメントの品質は、パフォーマンスを犠牲にして可能な限り最高になります。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  パフォーマンス指向の変換モードを有効にする場合、  false  無効にする場合。 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


この CadOptions オブジェクトが別のオブジェクトと等しいかどうかをチェックします。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | o | java.lang.Object | 比較対象となるオブジェクトです。 |
|

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードは
オブジェクトの内部状態に基づき、ハッシュベースのデータ構造で使用されます
ハッシュマップやハッシュセットなどです。
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - このオブジェクトのハッシュコード値。

### toString() {#toString--}
```
public String toString()
```


このオブジェクトの文字列表現を返します。
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - このオブジェクトの文字列表現。

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


このオブジェクトの文字列表現を返します。
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | スタイル | org.apache.commons.lang3.builder.ToStringStyle | 文字列表現を生成するために使用する ToStringStyle。 |
|

**Returns:**
java.lang.String - 指定された ToStringStyle を使用したこのオブジェクトの文字列表現。

