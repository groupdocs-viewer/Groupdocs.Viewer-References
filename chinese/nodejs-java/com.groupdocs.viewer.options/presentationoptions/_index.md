---
title: "PresentationOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于渲染演示文稿的选项。"
type: docs
weight: 26
url: /zh/nodejs-java/com.groupdocs.viewer.options/presentationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PresentationOptions
```

提供用于渲染演示文稿的选项。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationOptions()](#PresentationOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isRenderToPureHtml()](#isRenderToPureHtml--) | 为 Presentation 文档启用新的 HTML 渲染模式。 |
| [setRenderToPureHtml(boolean renderToPureHtml)](#setRenderToPureHtml-boolean-) | 为 Presentation 文档启用新的 HTML 渲染模式。 |
| [getResolution()](#getResolution--) | 演示文稿中图像的分辨率（仅用于 HTML/PDF 渲染）。 |
| [setResolution(Resolution resolution)](#setResolution-com.groupdocs.viewer.options.Resolution-) | 演示文稿中图像的分辨率（仅用于 HTML/PDF 渲染）。 |
### PresentationOptions() {#PresentationOptions--}
```
public PresentationOptions()
```


### isRenderToPureHtml() {#isRenderToPureHtml--}
```
public boolean isRenderToPureHtml()
```


为 Presentation 文档启用新的 HTML 渲染模式。

在此模式下，Presentation 文件被渲染为纯 HTML/CSS 标记，不包含 SVG 图像。默认情况下，此功能已禁用（false）。如果未启用此选项，将使用现有的基于 SVG 的 HTML 渲染器。

**Returns:**
boolean
### setRenderToPureHtml(boolean renderToPureHtml) {#setRenderToPureHtml-boolean-}
```
public void setRenderToPureHtml(boolean renderToPureHtml)
```


为 Presentation 文档启用新的 HTML 渲染模式。

在此模式下，Presentation 文件被渲染为纯 HTML/CSS 标记，不包含 SVG 图像。默认情况下，此功能已禁用（false）。如果未启用此选项，将使用现有的基于 SVG 的 HTML 渲染器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderToPureHtml | boolean |  |

### getResolution() {#getResolution--}
```
public Resolution getResolution()
```


演示文稿中图像的分辨率（仅用于 HTML/PDF 渲染）。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Returns:**
com.groupdocs.viewer.options.Resolution
### setResolution(Resolution resolution) {#setResolution-com.groupdocs.viewer.options.Resolution-}
```
public void setResolution(Resolution resolution)
```


演示文稿中图像的分辨率（仅用于 HTML/PDF 渲染）。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-presentations/#specify-image-resolution

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resolution | com.groupdocs.viewer.options.Resolution |  |

