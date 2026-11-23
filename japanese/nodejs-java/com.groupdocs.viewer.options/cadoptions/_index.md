---
title: "CadOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "CAD 図面のレンダリングオプションを提供します。"
type: docs
weight: 13
url: /ja/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD 図面のレンダリングオプションを提供します。

CadOptions クラスは、GroupDocs.Viewer コンポーネントで CAD 図面のレンダリングを制御するために使用できるさまざまな設定やパラメータをカプセル化します。

詳細情報とコード例については、[Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] と [Specify rendering options for CAD files][] を参照してください。

使用例:

```

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
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## フィールド

| フィールド | 説明 |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPc3File()](#getPc3File--) | プロッタに関連付けられた PC3（プロッタ構成）ファイルを取得します。 |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | プロッタに関連付けられた PC3（プロッタ構成）ファイルを設定します。 |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | スケールファクターでのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。 |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | 幅でのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。 |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | 高さでのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。 |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | 幅と高さでレンダリングするための CadOptions クラスの新しいインスタンスを初期化します。 |
| [getScaleFactor()](#getScaleFactor--) | レンダリングのスケール係数を取得します。 |
| [getWidth()](#getWidth--) | 出力結果の幅（ピクセル）を取得します。 |
| [getHeight()](#getHeight--) | 出力結果の高さ（ピクセル）を取得します。 |
| [getBackgroundColor()](#getBackgroundColor--) | 画像の背景色を取得します。 |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | 画像の背景色を取得します。 |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | 画像の背景色を設定します。 |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | 画像の背景色を設定します。 |
| [getTiles()](#getTiles--) | レンダリングする描画領域を取得します。 |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | レンダリングする描画領域を設定します。 |
| [isRenderLayouts()](#isRenderLayouts--) | CAD ドキュメントのレイアウトをレンダリングするかどうかを示します。 |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | CAD ドキュメントのレイアウトをレンダリングするかどうかを設定します。 |
| [getLayoutName()](#getLayoutName--) | レンダリングする特定のレイアウト名を取得します。 |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | レンダリングする特定のレイアウト名を設定します。 |
| [getLayers()](#getLayers--) | レンダリングする CAD 描画レイヤーを取得します。 |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | レンダリングする CAD 描画レイヤーを取得します。 |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | このフラグを true に設定すると、CAD ファミリ内のすべてのフォーマットに対して、パフォーマンス重視の特別な変換モードが有効になります。 |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | このフラグを true に設定すると、CAD ファミリ内のすべてのフォーマットに対して、パフォーマンス重視の特別な変換モードが有効になります。 |
| [equals(Object o)](#equals-java.lang.Object-) | この CadOptions オブジェクトが別のオブジェクトと等しいかどうかを確認します。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
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


プロッタに関連付けられた PC3（プロッタ構成）ファイルを取得します。

**Returns:**
java.lang.String - PC3 ファイルのパス。
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


プロッタに関連付けられた PC3（プロッタ構成）ファイルを設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pc3File | java.lang.String | PC3 ファイルのパス。 |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


スケールファクターでのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleFactor | double | レンダリングのスケール係数。1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。 |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


幅でのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | 出力結果の幅（ピクセル）。 |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


高さでのレンダリング用に CadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| height | int | 出力結果の高さ（ピクセル）。 |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


幅と高さでレンダリングするための CadOptions クラスの新しいインスタンスを初期化します。

コード例については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | int | 出力結果の幅（ピクセル）。 |
| height | int | 出力結果の高さ（ピクセル）。 |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


レンダリングのスケール係数を取得します。1 より大きい値は出力結果を拡大し、0 から 1 の間の値は出力結果を縮小します。

**Returns:**
double - レンダリングのスケール係数。
### getWidth() {#getWidth--}
```
public final int getWidth()
```


出力結果の幅（ピクセル）を取得します。

**Returns:**
int - 出力結果の幅。
### getHeight() {#getHeight--}
```
public final int getHeight()
```


出力結果の高さ（ピクセル）を取得します。

**Returns:**
int - 出力結果の高さ。
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


画像の背景色を取得します。

**Returns:**
java.awt.Color - 画像の背景色。
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


画像の背景色を取得します。

**Returns:**
java.lang.String - 画像の背景色（0xFFFFFF 形式）。
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


画像の背景色を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| backgroundColor | java.awt.Color | 画像の背景色。 |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


画像の背景色を設定します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| colorName | java.lang.String | 画像の背景色の名前。 |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


レンダリングする描画領域を取得します。

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - レンダリングする描画領域のリスト。
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


レンダリングする描画領域を設定します。

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | レンダリングする描画領域のリスト。 |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


CAD ドキュメントのレイアウトをレンダリングするかどうかを示します。

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  レイアウトをレンダリングする場合、  false  それ以外の場合。
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


CAD ドキュメントのレイアウトをレンダリングするかどうかを設定します。

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean | true  レイアウトをレンダリングする場合、  false  それ以外の場合。 |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


特定のレイアウトをレンダリングする名前を取得します。レイアウト名は大文字小文字を区別します。

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - 特定のレイアウトをレンダリングする名前。
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


特定のレイアウトをレンダリングする名前を設定します。レイアウト名は大文字小文字を区別します。

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 特定のレイアウトをレンダリングする名前。 |

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


レンダリングする CAD 描画レイヤーを取得します。

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD 描画レイヤー。
### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


レンダリングする CAD 描画レイヤーを取得します。

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | CAD 描画レイヤー。 |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


このフラグを true に設定すると、CAD ファミリ内のすべてのフォーマットに対して、特別なパフォーマンス指向の変換モードが有効になります。このモードでは変換速度が大幅に速くなりますが、生成されるドキュメントの品質は著しく低下します。デフォルトでは無効 (false) です。生成されるドキュメントの品質は、パフォーマンスを犠牲にして可能な限り最高になります。

**Returns:**
boolean -  true  パフォーマンス指向の変換モードが有効な場合、  false  それ以外の場合。
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


このフラグを true に設定すると、CAD ファミリ内のすべてのフォーマットに対して、特別なパフォーマンス指向の変換モードが有効になります。このモードでは変換速度が大幅に速くなりますが、生成されるドキュメントの品質は著しく低下します。デフォルトでは無効 (false) です。生成されるドキュメントの品質は、パフォーマンスを犠牲にして可能な限り最高になります。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  パフォーマンス指向の変換モードを有効にする場合、  false  無効にする場合。 |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


この CadOptions オブジェクトが別のオブジェクトと等しいかどうかを確認します。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| o | java.lang.Object | 比較対象のオブジェクト。 |

**Returns:**
boolean - オブジェクトが等しい場合は true、そうでない場合は false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


このオブジェクトのハッシュコード値を計算します。ハッシュコードはオブジェクトの内部状態に基づき、ハッシュマップやハッシュセットなどのハッシュベースのデータ構造で使用されます。

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - このオブジェクトのハッシュコード値。
### toString() {#toString--}
```
public String toString()
```


このオブジェクトの文字列表現を返します。

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - このオブジェクトの文字列表現。
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


このオブジェクトの文字列表現を返します。

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| スタイル | org.apache.commons.lang3.builder.ToStringStyle | 文字列表現を生成するために使用する ToStringStyle。 |

**Returns:**
java.lang.String - 指定された ToStringStyle を使用したこのオブジェクトの文字列表現。
