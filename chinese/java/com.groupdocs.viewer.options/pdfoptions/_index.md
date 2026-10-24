---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染 PDF 文档的选项。"
type: docs
weight: 22
url: /zh/java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

提供用于渲染 PDF 文档的选项。


PdfOptions 类封装了可用于的各种设置和参数
用于控制 GroupDocs.Viewer 组件中 PDF 文档的渲染。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)。


示例用法：

````

 PdfOptions options = new PdfOptions();
 options.setDisableCharsGrouping(true);
 options.setRenderTextAsImage(true);
 options.setEnableFontHinting(true);

 final HtmlViewOptions htmlViewOptions = HtmlViewOptions.forEmbeddedResources();
 htmlViewOptions.setPdfOptions(options);

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(htmlViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfOptions()](#PdfOptions--) | 初始化一个新的实例 |
PdfOptions
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isDisableCopyProtection()](#isDisableCopyProtection--) | 在渲染为 HTML 时关闭内容复制保护。 |
|
|  | [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | 在渲染为 HTML 时关闭内容复制保护。 |
|
|  | [isRenderTextAsImage()](#isRenderTextAsImage--) | 确定是否将源文本渲染为 HTML 中的图像。 |
|
|  | [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | 设置是否将源文本渲染为 HTML 中的图像。 |
|
|  | [isDisableCharsGrouping()](#isDisableCharsGrouping--) | 检查字符分组是否已禁用，以在页面渲染时保持字符定位的最大精度。 |
|
|  | [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | 设置禁用字符分组的选项，以确保在页面渲染时字符定位的最大精度。 |
|
|  | [isEnableLayeredRendering()](#isEnableLayeredRendering--) | 检查在渲染为 HTML 时，文本和图形的渲染是否应遵循原始 PDF 文档中的 Z 顺序。 |
|
|  | [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | 启用或禁用根据原始 PDF 文档中的 Z 顺序在渲染为 HTML 时渲染文本和图形。 |
|
|  | [isEnableFontHinting()](#isEnableFontHinting--) | 确定是否已启用字体微调。 |
|
|  | [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | 启用字体微调。 |
|
|  | [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | 启用将页面渲染为与源 PDF 文档页面大小相同的像素尺寸。 |
|
|  | [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | 启用将页面渲染为与源 PDF 文档页面大小相同的像素尺寸。 |
|
|  | [getImageQuality()](#getImageQuality--) | 检索在渲染为 HTML 时图像资源的输出图像质量。 |
|
|  | [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | 设置在渲染为 HTML 时图像资源的输出图像质量。 |
|
|  | [isFixedLayout()](#isFixedLayout--) | PDF 是一种固定格式，因此所有元素在页面上都有特定位置。 |
|
|  | [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF 是一种固定格式，因此所有元素在页面上都有特定位置。 |
|
|  | [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 启用此选项以在输出 HTML 文档中将每个图像包装在 SVG 标记中，以提高输出质量。 |
|
|  | [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 启用此选项以在输出 HTML 文档中将每个图像包装在 SVG 标记中，以提高输出质量。 |
|
|  | [isAnalyzeFonts()](#isAnalyzeFonts--) | 根据需要替换字体，以确保文本中的所有字符都能显示。 |
|
|  | [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | 根据需要替换字体，以确保文本中的所有字符都能显示。 |
|
|  | [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。 |
|
|  | [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 设置标志以禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。 |
|
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


初始化一个新的实例
PdfOptions
类。


### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


在渲染为 HTML 时关闭内容复制保护。


在将受防复制文本和图像保护的 PDF 文件渲染为 HTML 时，GroupDocs.Viewer 会向 HTML BODY 标记添加 'inert' HTML 属性。
此选项的默认值是
false
.


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)。


**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


在渲染为 HTML 时关闭内容复制保护。


在将受防复制文本和图像保护的 PDF 文件渲染为 HTML 时，GroupDocs.Viewer 会向 HTML BODY 标记添加 'inert' HTML 属性。
此选项的默认值是
false
.


有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


确定是否将源文本渲染为 HTML 中的图像。


当此选项设置为
true
，文本将在输出 HTML 中渲染为图像。
启用此选项可使文本不可选择，或修复字符渲染，使 HTML 看起来像 PDF。
在渲染为 HTML 时支持此选项。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  如果文本在 HTML 中渲染为图像，则为 true，否则为 false。

### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


设置是否将源文本渲染为 HTML 中的图像。


当此选项设置为
true
，文本将在输出 HTML 中渲染为图像。
启用此选项可使文本不可选择，或修复字符渲染，使 HTML 看起来像 PDF。
在渲染为 HTML 时支持此选项。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderTextAsImage | boolean | true  将文本渲染为 HTML 中的图像，  false  否则。 |
|

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


检查字符分组是否已禁用，以在页面渲染时保持字符定位的最大精度。
启用此选项后，字符将不进行任何分组渲染，从而确保最高精度。


***Note:** By default, character grouping is enabled.*
转换 PDF 文件时，GroupDocs.Viewer 会将单个字符分组为单词，以提升渲染性能。如果文档包含象形文字或特殊符号，您可能希望禁止字符分组，以确保更精确的布局。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)。


**Returns:**
布尔型 -  true  表示字符分组已禁用，  false  表示未禁用。

### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


设置禁用字符分组的选项，以确保在页面渲染时字符定位的最大精度。
当通过将值设置为以下内容启用此选项时
true
，字符分组被禁用，从而确保最高精度。


***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.*
转换 PDF 文件时，GroupDocs.Viewer 会将单个字符分组为单词，以提升渲染性能。如果文档包含象形文字或特殊符号，您可能希望禁止字符分组，以确保更精确的布局。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  禁用字符分组，  false  启用字符分组。 |
|

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


检查在渲染为 HTML 时，文本和图形的渲染是否应遵循原始 PDF 文档中的 Z 顺序。
当通过返回以下内容启用此选项时
true
，文本和图形将按照原始 PDF 文档中的 Z 顺序进行渲染。


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
默认情况下，GroupDocs.Veiewer 将文本和图形渲染为 HTML 中的单层。此选项允许您按源文件中的相同顺序排列对象。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)。


**Returns:**
布尔型 -  true  表示已启用分层渲染，  false  表示未启用。

### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


启用或禁用根据原始 PDF 文档中的 Z 顺序在渲染为 HTML 时渲染文本和图形。


***Note:** By default, text and graphics are rendered into HTML as a single layer.*
默认情况下，GroupDocs.Veiewer 将文本和图形渲染为 HTML 中的单层。此选项允许您按源文件中的相同顺序排列对象。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用分层渲染，  false  禁用分层渲染。 |
|

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


确定是否启用字体微调。字体微调会调整轮廓字体的显示方式。
此选项仅在源文档使用 TrueType (TTF) 字体时受支持。


***Note:** This option is supported when rendering into PNG or JPG formats.*
字体微调会调整轮廓字体的显示方式。仅适用于源文档中使用的 TTF 字体。此选项可用于渲染为 PNG 或 JPG 格式。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)。


**Returns:**
布尔型 -  true  表示已启用字体微调，  false  表示未启用。

### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


启用字体微调。字体微调会调整轮廓字体的显示，并且仅在源文档使用 TrueType (TTF) 字体时受支持。


***Note:** This option is supported when rendering into PNG or JPG formats.*
字体微调会调整轮廓字体的显示方式。仅适用于源文档中使用的 TTF 字体。此选项可用于渲染为 PNG 或 JPG 格式。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用字体微调，  false  禁用字体微调。 |
|

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


启用将页面渲染为与源 PDF 文档页面大小相同的像素尺寸。


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
默认情况下，GroupDocs.Viewer 会计算输出图像的页面大小以获得更好的渲染质量。启用此选项可确保输出页面的尺寸与源 PDF 文档的页面尺寸（以像素为单位）相同。默认值为 false。
此选项可用于渲染为 PNG 或 JPG 格式。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)。


**Returns:**
布尔型 -  true  表示已启用此选项，  false  表示未启用。

### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


启用将页面渲染为与源 PDF 文档页面大小相同的像素尺寸。


***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.*
默认情况下，GroupDocs.Viewer 会计算输出图像的页面大小以获得更好的渲染质量。启用此选项可确保输出页面的尺寸与源 PDF 文档的页面尺寸（以像素为单位）相同。默认值为 false。
此选项可用于渲染为 PNG 或 JPG 格式。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | renderOriginalPageSize | boolean | true  以启用使用原始页面大小渲染，  false  表示否则。 |
|

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


检索在渲染为 HTML 时图像资源的输出图像质量。默认值为 Low。


当此选项设置为 true 时，GroupDocs.Viewer 在 HTML 输出中将文本渲染为图像。这使得文本不可选择，并提升字符渲染，确保在 HTML 中呈现类似 PDF 的外观。默认值为 false。
此选项可用于渲染为 HTML。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)。


**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.

### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


设置在渲染为 HTML 时图像资源的输出图像质量。默认值为 Low。


当此选项设置为 true 时，GroupDocs.Viewer 在 HTML 输出中将文本渲染为图像。这使得文本不可选择，并提升字符渲染，确保在 HTML 中呈现类似 PDF 的外观。默认值为 false。
此选项可用于渲染为 HTML。
有关代码示例，请参阅[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | 在渲染为 HTML 时图像资源的输出图像质量。 |
|

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF 是一种固定格式，因此所有元素在页面上都有特定位置。
为了确保输出的 HTML 与源 PDF 看起来相同，文档默认以固定布局渲染为 HTML。
使用固定布局渲染时，输出的 HTML 具有固定尺寸，因此元素无论窗口大小如何都会保持在相同位置。
要以流式布局渲染为 HTML，请将此属性设置为 false。


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF 和 EPUB 文档最初以固定布局渲染为 HTML，以保持源文档的外观。此固定布局意味着所有 HTML 元素在具有固定尺寸的容器内拥有精确位置。调整浏览器窗口大小不会影响文档中元素的位置和尺寸。
此选项仅在渲染为 HTML 时可用。默认值为 true。要以流式布局渲染，请将此属性设置为 false。


示例用法：

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Returns:**
boolean - 如果是固定布局则为 true

### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF 是一种固定格式，因此所有元素在页面上都有特定位置。
为了确保输出的 HTML 与源 PDF 看起来相同，文档默认以固定布局渲染为 HTML。
使用固定布局渲染时，输出的 HTML 具有固定尺寸，因此元素无论窗口大小如何都会保持在相同位置。
要以流式布局渲染为 HTML，请将此属性设置为 false。


***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.*
PDF 和 EPUB 文档最初以固定布局渲染为 HTML，以保持源文档的外观。此固定布局意味着所有 HTML 元素在具有固定尺寸的容器内拥有精确位置。调整浏览器窗口大小不会影响文档中元素的位置和尺寸。
此选项仅在渲染为 HTML 时可用。默认值为 true。要以流式布局渲染，请将此属性设置为 false。


示例用法：

````

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | fixedLayout | boolean | 如果是固定布局则为 true |
|

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


启用此选项以在输出 HTML 文档中将每个图像包装在 SVG 标记中，以提高输出质量。


此选项在将 [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) 渲染为带有嵌入和外部资源的 HTML 时受支持。


默认情况下，将渲染为 PDF 和页面布局文件时，所有图像会渲染为一个 PNG 图像。渲染后的 PNG 图像用作输出 HTML 文档的背景。


了解更多：

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Returns:**
boolean -  true  如果图像被包装在 SVG 中，则为 true，  false  否则。

### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


启用此选项以在输出 HTML 文档中将每个图像包装在 SVG 标记中，以提高输出质量。


此选项在将 [PDF and Page Layout file formats](../https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats) 渲染为带有嵌入和外部资源的 HTML 时受支持。


默认情况下，将渲染为 PDF 和页面布局文件时，所有图像会渲染为一个 PNG 图像。渲染后的 PNG 图像用作输出 HTML 文档的背景。


了解更多：

* [Render PDF documents as HTML and image files](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/)
* [Render to HTML](../https://docs.groupdocs.com/viewer/java/rendering-to-html/)

<br />



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | wrapImagesInSvg | boolean | true  如果图像应包装在 SVG 中，则为 true，  false  否则。 |
|

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


根据需要替换字体，以确保文本中的所有字符都能显示。


**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


根据需要替换字体，以确保文本中的所有字符都能显示。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | analyzeFonts | boolean | true 如果应显示字体，则为 true， false 否则。 |
|

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。


如果这些操作被该字体的许可证禁止，则许多字体相关的操作无法执行。
例如，如果许可证规则禁用嵌入，则某些字体无法嵌入到 PDF 文档中。
使用此标志时请小心。设置后，意味着设置此标志的人承担全部责任
对可能的许可证/法律违规自行负责。因此他们自行承担风险。强烈建议使用
仅在您完全确信未侵犯版权法时才使用此标志。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)。


示例用法：

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


设置标志以禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。


如果这些操作被该字体的许可证禁止，则许多字体相关的操作无法执行。
例如，如果许可证规则禁用嵌入，则某些字体无法嵌入到 PDF 文档中。
使用此标志时请小心。设置后，意味着设置此标志的人承担全部责任
对可能的许可证/法律违规自行负责。因此他们自行承担风险。强烈建议使用
仅在您完全确信未侵犯版权法时才使用此标志。默认值为 false。
代码示例请参见[文档](../https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files)。


示例用法：

````

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
````



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

