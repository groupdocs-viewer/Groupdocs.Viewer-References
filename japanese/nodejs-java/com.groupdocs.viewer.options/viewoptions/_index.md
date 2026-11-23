---
title: "ViewOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "レンダリングオプションを含みます。"
type: docs
weight: 35
url: /ja/nodejs-java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

レンダリングオプションを含みます。

ViewOptions クラスは BaseViewOptions クラスを継承し、GroupDocs.Viewer コンポーネントのレンダリングオプションの基底クラスとして機能します。さまざまな種類のドキュメントを異なる形式にレンダリングするために使用できる共通の設定とパラメータをカプセル化します。

***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWatermark()](#getWatermark--) | 各ページに適用されるテキスト透かしを取得します。 |
| [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | 各ページに適用されるテキスト透かしを設定します。 |
| [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | 指定されたページに時計回りの回転を適用します。 |
| [getPageRotations()](#getPageRotations--) | ページの回転を取得します。 |
| [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | インスタンスが空であるか確認するだけのために作成するのを防止するために |
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


各ページに適用されるテキスト透かしを取得します。

両方の \#setWatermark(Watermark).setWatermark(Watermark) と \#getPageRotations().getPageRotations() が指定されている場合、透かしは回転したページに適用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.
### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


各ページに適用されるテキスト透かしを設定します。

両方の  ViewOptions.Watermark  と \#getPageRotations().getPageRotations() が指定されている場合、透かしは回転したページに適用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/add-text-watermark/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Watermark](../../com.groupdocs.viewer.options/watermark) | 設定するテキスト透かし。 |

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


指定されたページに時計回りの回転を適用します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pageNumber | int | ページ番号は、0 より大きくなければなりません。 |
| rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | 回転値。 |

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


ページの回転を取得します。

両方の [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions\#setWatermark-Watermark-) と getPageRotations() が指定されている場合、透かしは回転したページに適用されます。詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/

**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - キーがページ番号で、値がそれぞれの回転を表すマップ。
### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


インスタンスが空であるか確認するだけのために作成するのを防止するために

**Returns:**
boolean
