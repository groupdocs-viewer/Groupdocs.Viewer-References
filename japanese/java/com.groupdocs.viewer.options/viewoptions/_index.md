---
title: "ViewOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "レンダリングオプションを含みます。"
type: docs
weight: 35
url: /ja/java/com.groupdocs.viewer.options/viewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions)
```
public abstract class ViewOptions extends BaseViewOptions
```

レンダリングオプションを含みます。


ViewOptions クラスは BaseViewOptions クラスを継承し、レンダリングオプションの基底クラスとして機能します
GroupDocs.Viewer コンポーネント内です。共通の設定や使用できるパラメータをカプセル化します
さまざまな種類のドキュメントを異なる形式にレンダリングするためです。


***Note:** The ViewOptions class should not be used directly, use [HtmlViewOptions](../../com.groupdocs.viewer.options/htmlviewoptions), [PdfViewOptions](../../com.groupdocs.viewer.options/pdfviewoptions), [PngViewOptions](../../com.groupdocs.viewer.options/pngviewoptions) and so on instead.*

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ViewOptions()](#ViewOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWatermark()](#getWatermark--) | 各ページに適用されるテキスト透かしを取得します。 |
|
|  | [setWatermark(Watermark value)](#setWatermark-com.groupdocs.viewer.options.Watermark-) | 各ページに適用するテキスト透かしを設定します。 |
|
|  | [rotatePage(int pageNumber, Rotation rotation)](#rotatePage-int-com.groupdocs.viewer.options.Rotation-) | 指定されたページに時計回りの回転を適用します。 |
|
|  | [getPageRotations()](#getPageRotations--) | ページの回転情報を取得します。 |
|
|  | [isPageRotationsInitialized_Internal()](#isPageRotationsInitialized-Internal--) | インスタンスが空であるか確認するだけのために作成するのを防ぐために |
|
### ViewOptions() {#ViewOptions--}
```
public ViewOptions()
```


### getWatermark() {#getWatermark--}
```
public final Watermark getWatermark()
```


各ページに適用されるテキスト透かしを取得します。


#setWatermark(Watermark).setWatermark(Watermark) と #getPageRotations().getPageRotations() の両方が指定されている場合、
透かしは回転されたページに適用されます。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/add-text-watermark/) を参照してください。


**Returns:**
[Watermark](../../com.groupdocs.viewer.options/watermark) - the text watermark applied to each page.

### setWatermark(Watermark value) {#setWatermark-com.groupdocs.viewer.options.Watermark-}
```
public final void setWatermark(Watermark value)
```


各ページに適用するテキスト透かしを設定します。


両方の場合
ViewOptions.Watermark
#getPageRotations().getPageRotations() が指定されている場合、
透かしは回転されたページに適用されます。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/add-text-watermark/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | value | [Watermark](../../com.groupdocs.viewer.options/watermark) | 設定するテキスト透かしです。 |
|

### rotatePage(int pageNumber, Rotation rotation) {#rotatePage-int-com.groupdocs.viewer.options.Rotation-}
```
public final void rotatePage(int pageNumber, Rotation rotation)
```


指定されたページに時計回りの回転を適用します。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
|  | pageNumber | int | ページ番号は 0 より大きい必要があります。 |
|
|  | rotation | [Rotation](../../com.groupdocs.viewer.options/rotation) | 回転値です。 |
|

### getPageRotations() {#getPageRotations--}
```
public Map<Integer,Rotation> getPageRotations()
```


ページの回転情報を取得します。


両方の [setWatermark(Watermark)](../../com.groupdocs.viewer.options/viewoptions#setWatermark-Watermark-) がある場合、
getPageRotations()
が指定されている場合、
透かしは回転されたページに適用されます。
詳細については、[ドキュメント](../https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/) を参照してください。


**Returns:**
java.util.Map<java.lang.Integer,com.groupdocs.viewer.options.Rotation> - キーがページ番号で、値が対応する回転を表すマップです。

### isPageRotationsInitialized_Internal() {#isPageRotationsInitialized-Internal--}
```
public boolean isPageRotationsInitialized_Internal()
```


インスタンスが空であるか確認するだけのために作成するのを防ぐために


**Returns:**
boolean
