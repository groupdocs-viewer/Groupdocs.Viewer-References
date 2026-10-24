---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染演示文稿的选项。"
type: docs
weight: 26
url: /zh/java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

提供用于渲染演示文稿的选项。


有关详细信息，请参阅 [documentation](../https://docs.groupdocs.com/viewer/java/render-presentations/).

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isRenderToPureHtml()](#isRenderToPureHtml--) | 为演示文稿文档启用新的 HTML 渲染模式。 |
|
|  | [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | 为演示文稿文档启用新的 HTML 渲染模式。 |
|
|  | [isRenderHeaderFooterPlaceholders()](#isRenderHeaderFooterPlaceholders--) | 在幻灯片的页眉和页脚中启用占位符渲染。 |
|
|  | [setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)](#setRenderHeaderFooterPlaceholders-boolean-) | 在幻灯片的页眉和页脚中启用占位符渲染。 |
|
|  | [getResolution()](#getResolution--) | 演示文稿内部图像的分辨率（仅用于 HTML/PDF 渲染）。 |
|
|  | [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | 演示文稿内部图像的分辨率（仅用于 HTML/PDF 渲染）。 |
|
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


为演示文稿文档启用新的 HTML 渲染模式。


在此模式下，演示文稿文件将渲染为纯 HTML/CSS 标记，不包含 SVG 图像。
默认情况下，此功能已禁用（false）。如果未启用此选项，将使用现有的基于 SVG 的 HTML 渲染器。


**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


为演示文稿文档启用新的 HTML 渲染模式。


在此模式下，演示文稿文件将渲染为纯 HTML/CSS 标记，不包含 SVG 图像。
默认情况下，此功能已禁用（false）。如果未启用此选项，将使用现有的基于 SVG 的 HTML 渲染器。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### isRenderHeaderFooterPlaceholders() {#isRenderHeaderFooterPlaceholders--}
```
public boolean isRenderHeaderFooterPlaceholders()
```


启用在幻灯片的页眉和页脚中渲染占位符。默认情况下禁用（false）。此选项适用于演示文稿的所有四种渲染模式：HTML、PDF、PNG 和 JPEG。在使用 . 时不适用。


**Returns:**
boolean
### setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders) {#setRenderHeaderFooterPlaceholders-boolean-}
```
public void setRenderHeaderFooterPlaceholders(boolean renderHeaderFooterPlaceholders)
```


启用在幻灯片的页眉和页脚中渲染占位符。默认情况下禁用（false）。此选项适用于演示文稿的所有四种渲染模式：HTML、PDF、PNG 和 JPEG。在使用 . 时不适用。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderHeaderFooterPlaceholders | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


演示文稿内部图像的分辨率（仅用于 HTML/PDF 渲染）。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution)。


**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


演示文稿内部图像的分辨率（仅用于 HTML/PDF 渲染）。


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

