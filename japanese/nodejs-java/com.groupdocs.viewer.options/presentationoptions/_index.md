---
title: "PresentationOptions"
second_title: "Java 経由の Node.js 用 GroupDocs.Viewer API リファレンス"
description: "プレゼンテーションのレンダリングオプションを提供します。"
type: docs
weight: 26
url: /ja/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

プレゼンテーションのレンダリングオプションを提供します。

詳細については、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | Presentation ドキュメント用の新しい HTML レンダリングモードを有効にします。 |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | Presentation ドキュメント用の新しい HTML レンダリングモードを有効にします。 |
| [getResolution()](#getResolution--) | プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。 |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。 |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


Presentation ドキュメント用の新しい HTML レンダリングモードを有効にします。

このモードでは、Presentation ファイルは SVG 画像を使用せず、純粋な HTML/CSS マークアップにレンダリングされます。デフォルトでは、この機能は無効 (false) です。このオプションが有効になっていない場合、既存の SVG ベースの HTML レンダラーが使用されます。

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


Presentation ドキュメント用の新しい HTML レンダリングモードを有効にします。

このモードでは、Presentation ファイルは SVG 画像を使用せず、純粋な HTML/CSS マークアップにレンダリングされます。デフォルトでは、この機能は無効 (false) です。このオプションが有効になっていない場合、既存の SVG ベースの HTML レンダラーが使用されます。

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。

コードサンプルについては、[documentation][] を参照してください。


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

