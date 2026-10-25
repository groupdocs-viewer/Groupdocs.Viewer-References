---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Java API リファレンス"
description: "プレゼンテーションのレンダリングオプションを提供します。"
type: docs
weight: 26
url: /ja/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

プレゼンテーションのレンダリングオプションを提供します。


詳細については、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/) を参照してください。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | プレゼンテーション文書に対して新しい HTML レンダリングモードを有効にします。 |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | プレゼンテーション文書に対して新しい HTML レンダリングモードを有効にします。 |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | スライドのヘッダーとフッターにプレースホルダーのレンダリングを有効にします。 |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | スライドのヘッダーとフッターにプレースホルダーのレンダリングを有効にします。 |
|
|  | [getResolution()](#getResolution--) | プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。 |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。 |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


プレゼンテーション文書に対して新しい HTML レンダリングモードを有効にします。


このモードでは、プレゼンテーションファイルが SVG 画像なしで純粋な HTML/CSS マークアップにレンダリングされます。
デフォルトでは、この機能は無効（false）です。このオプションが有効でない場合、既存の SVG ベースの HTML レンダラーが使用されます。


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


プレゼンテーション文書に対して新しい HTML レンダリングモードを有効にします。


このモードでは、プレゼンテーションファイルが SVG 画像なしで純粋な HTML/CSS マークアップにレンダリングされます。
デフォルトでは、この機能は無効（false）です。このオプションが有効でない場合、既存の SVG ベースの HTML レンダラーが使用されます。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


スライドのヘッダーとフッターにプレースホルダーのレンダリングを有効にします。デフォルトでは無効（false）です。このオプションはプレゼンテーションの 4 つのレンダリングモードすべて（HTML、PDF、PNG、JPEG）に適用されます。純粋な HTML/CSS マークアップへのレンダリング時に使用する場合は適用されません。


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


スライドのヘッダーとフッターにプレースホルダーのレンダリングを有効にします。デフォルトでは無効（false）です。このオプションはプレゼンテーションの 4 つのレンダリングモードすべて（HTML、PDF、PNG、JPEG）に適用されます。純粋な HTML/CSS マークアップへのレンダリング時に使用する場合は適用されません。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution) を参照してください。


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


プレゼンテーション内の画像の解像度（HTML/PDF レンダリング時のみ）。


コードサンプルについては、[documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution) を参照してください。


**Parameters:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

