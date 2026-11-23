---
title: "PdfOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供用于渲染 PDF 文档的选项。"
type: docs
weight: 22
url: /zh/nodejs-java/com.groupdocs.viewer.options/pdfoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptions
```

提供用于渲染 PDF 文档的选项。

PdfOptions 类封装了各种设置和参数，可用于控制 GroupDocs.Viewer 组件中 PDF 文档的渲染。有关详细信息，请参阅 [documentation][].

示例用法：

```

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
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | 初始化 PdfOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isDisableCopyProtection()](#isDisableCopyProtection--) | 在渲染为 HTML 时关闭内容复制保护。 |
| [setDisableCopyProtection(boolean disableCopyProtection)](#setDisableCopyProtection-boolean-) | 在渲染为 HTML 时关闭内容复制保护。 |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | 确定是否将来源文本渲染为 HTML 中的图像。 |
| [setRenderTextAsImage(boolean renderTextAsImage)](#setRenderTextAsImage-boolean-) | 设置是否将来源文本渲染为 HTML 中的图像。 |
| [isDisableCharsGrouping()](#isDisableCharsGrouping--) | 检查字符分组是否已禁用，以在页面渲染时保持字符定位的最大精度。 |
| [setDisableCharsGrouping(boolean value)](#setDisableCharsGrouping-boolean-) | 设置禁用字符分组的选项，以确保页面渲染时字符定位的最大精度。 |
| [isEnableLayeredRendering()](#isEnableLayeredRendering--) | 检查在渲染为 HTML 时，文本和图形的渲染是否应遵循原始 PDF 文档中的 Z 顺序。 |
| [setEnableLayeredRendering(boolean value)](#setEnableLayeredRendering-boolean-) | 在渲染为 HTML 时，根据原始 PDF 文档中的 Z 顺序启用或禁用文本和图形的渲染。 |
| [isEnableFontHinting()](#isEnableFontHinting--) | 确定是否已启用字体微调。 |
| [setEnableFontHinting(boolean value)](#setEnableFontHinting-boolean-) | 启用字体微调。 |
| [isRenderOriginalPageSize()](#isRenderOriginalPageSize--) | 启用将页面渲染为与源 PDF 文档页面大小相同像素尺寸的功能。 |
| [setRenderOriginalPageSize(boolean renderOriginalPageSize)](#setRenderOriginalPageSize-boolean-) | 启用将页面渲染为与源 PDF 文档页面大小相同像素尺寸的功能。 |
| [getImageQuality()](#getImageQuality--) | 检索在渲染为 HTML 时图像资源的输出图像质量。 |
| [setImageQuality(ImageQuality value)](#setImageQuality-com.groupdocs.viewer.options.ImageQuality-) | 设置在渲染为 HTML 时图像资源的输出图像质量。 |
| [isFixedLayout()](#isFixedLayout--) | PDF 是一种固定格式，因此所有元素在页面上都有特定位置。 |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) | PDF 是一种固定格式，因此所有元素在页面上都有特定位置。 |
| [isWrapImagesInSvg()](#isWrapImagesInSvg--) | 启用此选项可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。 |
| [setWrapImagesInSvg(boolean wrapImagesInSvg)](#setWrapImagesInSvg-boolean-) | 启用此选项可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。 |
| [isFixLinkIssue()](#isFixLinkIssue--) | 尝试修复整个 HTML 页面内容为链接时的问题。 |
| [setFixLinkIssue(boolean fixLinkIssue)](#setFixLinkIssue-boolean-) | 尝试修复整个 HTML 页面内容为链接时的问题。 |
| [isAnalyzeFonts()](#isAnalyzeFonts--) | 根据需要替换字体，以确保文本中的所有字符均可显示。 |
| [setAnalyzeFonts(boolean analyzeFonts)](#setAnalyzeFonts-boolean-) | 根据需要替换字体，以确保文本中的所有字符均可显示。 |
| [isDisableFontLicenseVerifications()](#isDisableFontLicenseVerifications--) | 禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。 |
| [setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)](#setDisableFontLicenseVerifications-boolean-) | 设置标志以禁用当前 XPS/OXPS 文档中所有字体的任何许可证限制。 |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


初始化 PdfOptions 类的新实例。

### isDisableCopyProtection() {#isDisableCopyProtection--}
```
public boolean isDisableCopyProtection()
```


在渲染为 HTML 时关闭内容复制保护。

在将受防止复制文本和图像保护的 PDF 文件渲染为 HTML 时，GroupDocs.Viewer 会向 HTML BODY 标签添加 'inert' HTML 属性。此选项的默认值为 false。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Returns:**
boolean
### setDisableCopyProtection(boolean disableCopyProtection) {#setDisableCopyProtection-boolean-}
```
public void setDisableCopyProtection(boolean disableCopyProtection)
```


在渲染为 HTML 时关闭内容复制保护。

在将受防止复制文本和图像保护的 PDF 文件渲染为 HTML 时，GroupDocs.Viewer 会向 HTML BODY 标签添加 'inert' HTML 属性。此选项的默认值为 false。

代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-pdf-documents/#disable-copy-protection

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| disableCopyProtection | boolean |  |

### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


确定是否将来源文本渲染为 HTML 中的图像。

当此选项设置为 true 时，文本将在输出的 HTML 中渲染为图像。启用此选项可使文本不可选择，或修复字符渲染，使 HTML 看起来像 PDF。此选项在渲染为 HTML 时受支持。

***Note:** The default value is  false .*

**Returns:**
布尔型 - true 表示文本在 HTML 中渲染为图像，false 表示否则。
### setRenderTextAsImage(boolean renderTextAsImage) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean renderTextAsImage)
```


设置是否将来源文本渲染为 HTML 中的图像。

当此选项设置为 true 时，文本将在输出的 HTML 中渲染为图像。启用此选项可使文本不可选择，或修复字符渲染，使 HTML 看起来像 PDF。此选项在渲染为 HTML 时受支持。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderTextAsImage | boolean | true 表示在 HTML 中将文本渲染为图像，false 表示否则。 |

### isDisableCharsGrouping() {#isDisableCharsGrouping--}
```
public final boolean isDisableCharsGrouping()
```


检查在渲染页面时是否禁用了字符分组，以在字符定位期间保持最高精度。启用此选项后，字符将不进行任何分组渲染，从而确保最高精度。

***Note:** By default, character grouping is enabled.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Returns:**
布尔型 - true 表示字符分组已禁用，false 表示否则。
### setDisableCharsGrouping(boolean value) {#setDisableCharsGrouping-boolean-}
```
public final void setDisableCharsGrouping(boolean value)
```


设置此选项以禁用字符分组，在渲染页面时确保字符定位的最高精度。将该值设为 true 时启用此选项，字符分组将被禁用，从而确保最高精度。

***Note:** Disabling character grouping can help preserve the exact positioning of characters on the rendered page.* When converting PDF files, GroupDocs.Viewer groups individual characters into words for enhanced rendering performance. If your document includes hieroglyphics or special symbols, you might want to prohibit character grouping to ensure a more precise layout. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#disable-character-grouping

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true 表示禁用字符分组，false 表示启用它。 |

### isEnableLayeredRendering() {#isEnableLayeredRendering--}
```
public final boolean isEnableLayeredRendering()
```


检查在渲染为 HTML 时，文本和图形的渲染是否应遵循原始 PDF 文档中的 Z 顺序。将此选项设为 true 时，文本和图形将按照原始 PDF 文档中的 Z 顺序进行渲染。

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Returns:**
布尔型 - true 表示已启用分层渲染，false 表示否则。
### setEnableLayeredRendering(boolean value) {#setEnableLayeredRendering-boolean-}
```
public final void setEnableLayeredRendering(boolean value)
```


在渲染为 HTML 时，根据原始 PDF 文档中的 Z 顺序启用或禁用文本和图形的渲染。

***Note:** By default, text and graphics are rendered into HTML as a single layer.* By default, GroupDocs.Veiewer renders text and graphics as a single layer in HTML. This option lets you arrange objects in the same order as in the source file. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-multi-layer-rendering

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true 表示启用分层渲染，false 表示禁用它。 |

### isEnableFontHinting() {#isEnableFontHinting--}
```
public final boolean isEnableFontHinting()
```


确定是否启用字体微调。字体微调会调整轮廓字体的显示。此选项仅在源文档使用 TrueType (TTF) 字体时受支持。

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Returns:**
布尔型 - true 表示已启用字体微调，false 表示否则。
### setEnableFontHinting(boolean value) {#setEnableFontHinting-boolean-}
```
public final void setEnableFontHinting(boolean value)
```


启用字体微调。字体微调会调整轮廓字体的显示，仅在源文档使用 TrueType (TTF) 字体时受支持。

***Note:** This option is supported when rendering into PNG or JPG formats.* Font hinting adjusts how an outline font is displayed. Only applicable to TTF fonts used in the source document. This option is available for rendering to PNG or JPG formats. The default value is false. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#enable-font-hinting

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true 表示启用字体微调，false 表示禁用它。 |

### isRenderOriginalPageSize() {#isRenderOriginalPageSize--}
```
public boolean isRenderOriginalPageSize()
```


启用将页面渲染为与源 PDF 文档页面大小相同像素尺寸的功能。

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Returns:**
布尔型 - true 表示选项已启用，false 表示否则。
### setRenderOriginalPageSize(boolean renderOriginalPageSize) {#setRenderOriginalPageSize-boolean-}
```
public void setRenderOriginalPageSize(boolean renderOriginalPageSize)
```


启用将页面渲染为与源 PDF 文档页面大小相同像素尺寸的功能。

***Note:** By default, GroupDocs.Viewer calculates the output image page size for better rendering quality.* By default, GroupDocs.Viewer calculates output image page size for better rendering quality. Enable this option to ensure the output pages have the same size as the source PDF document's page size (in pixels). The default value is false. This option is available for rendering to PNG or JPG formats. For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#preserve-the-size-of-document-pages

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| renderOriginalPageSize | boolean | true 表示启用使用原始页面尺寸的渲染，false 表示否则。 |

### getImageQuality() {#getImageQuality--}
```
public final ImageQuality getImageQuality()
```


检索在渲染为 HTML 时图像资源的输出图像质量。默认值为 Low。

当此选项设置为 true 时，GroupDocs.Viewer 会在 HTML 输出中将文本渲染为图像。这使得文本不可选择，并提升字符渲染，使 HTML 看起来像 PDF。默认值为 false。此选项可用于渲染为 HTML。代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Returns:**
[ImageQuality](../../com.groupdocs.viewer.options/imagequality) - the output image quality for image resources when rendering into HTML.
### setImageQuality(ImageQuality value) {#setImageQuality-com.groupdocs.viewer.options.ImageQuality-}
```
public final void setImageQuality(ImageQuality value)
```


设置在渲染为 HTML 时图像资源的输出图像质量。默认值为 Low。

当此选项设置为 true 时，GroupDocs.Viewer 会在 HTML 输出中将文本渲染为图像。这使得文本不可选择，并提升字符渲染，使 HTML 看起来像 PDF。默认值为 false。此选项可用于渲染为 HTML。代码示例请参见 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#render-text-as-an-image

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ImageQuality](../../com.groupdocs.viewer.options/imagequality) | 在渲染为 HTML 时，图像资源的输出图像质量。 |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```


PDF 是一种固定格式，因此所有元素在页面上都有特定位置。为了确保输出的 HTML 与源 PDF 看起来相同，文档默认以固定布局渲染为 HTML。使用固定布局渲染时，输出的 HTML 大小固定，元素将在相同位置保持不变，无论窗口大小如何。若要以流式布局渲染为 HTML，请将此属性设为 false。

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

示例用法：

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Returns:**
布尔型 - 如果是固定布局则为 true
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```


PDF 是一种固定格式，因此所有元素在页面上都有特定位置。为了确保输出的 HTML 与源 PDF 看起来相同，文档默认以固定布局渲染为 HTML。使用固定布局渲染时，输出的 HTML 大小固定，元素将在相同位置保持不变，无论窗口大小如何。若要以流式布局渲染为 HTML，请将此属性设为 false。

***Note:** The default value is true. This option is supported when rendering into HTML. When rendering to fluid layout images are skipped. Use fluid layout when rendering PDF documents with textual content.* PDF and EPUB documents are initially rendered to HTML with a fixed layout to maintain the appearance of the source document. This fixed layout means all HTML elements have precise positions within a container with a set size. Resizing the browser window is not affect the position and size of elements in the document. This option is only available when rendering to HTML. The default value is true. To render with a fluid layout, set this property to false.

示例用法：

```

 try (Viewer viewer = new Viewer("resume.pdf")) {
      HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources("page_{0}.html");
      viewOptions.setFixedLayout(false);
      viewer.view(viewOptions);
 }
 
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fixedLayout | boolean | 如果是固定布局则为 true |

### isWrapImagesInSvg() {#isWrapImagesInSvg--}
```
public boolean isWrapImagesInSvg()
```


启用此选项可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。

当将 [PDF and Page Layout file formats][] 渲染为带有嵌入式和外部资源的 HTML 时，支持此选项。

默认情况下，将 PDF 和页面布局文件渲染时，所有图像会合并为一个 PNG 图像。渲染后的 PNG 图像用作输出 HTML 文档的背景。

了解更多：

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Returns:**
布尔型 - 如果图像被包装在 SVG 中则为 true，否则为 false。
### setWrapImagesInSvg(boolean wrapImagesInSvg) {#setWrapImagesInSvg-boolean-}
```
public void setWrapImagesInSvg(boolean wrapImagesInSvg)
```


启用此选项可将输出 HTML 文档中的每个图像包装在 SVG 标签中，以提升输出质量。

当将 [PDF and Page Layout file formats][] 渲染为带有嵌入式和外部资源的 HTML 时，支持此选项。

默认情况下，将 PDF 和页面布局文件渲染时，所有图像会合并为一个 PNG 图像。渲染后的 PNG 图像用作输出 HTML 文档的背景。

了解更多：

 *  [Render PDF documents as HTML and image files][]
 *  [Render to HTML][]


[PDF and Page Layout file formats]: https://docs.groupdocs.com/viewer/java/supported-document-formats/#pdf-and-page-layout-file-formats
[Render PDF documents as HTML and image files]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/
[Render to HTML]: https://docs.groupdocs.com/viewer/java/rendering-to-html/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wrapImagesInSvg | boolean | 如果图像应被包装在 SVG 中则为 true，否则为 false。 |

### isFixLinkIssue() {#isFixLinkIssue--}
```
public boolean isFixLinkIssue()
```


尝试修复整个 HTML 页面内容为链接时的问题。仅在输入格式为 PDF 且输出格式为 HTML（带嵌入式或外部资源）时有效。默认情况下此功能已禁用（false）。仅在明确了解原因并确定需要时才开启此选项。开启此选项会增加文档处理时间。

**Returns:**
boolean
### setFixLinkIssue(boolean fixLinkIssue) {#setFixLinkIssue-boolean-}
```
public void setFixLinkIssue(boolean fixLinkIssue)
```


尝试修复整个 HTML 页面内容为链接时的问题。仅在输入格式为 PDF 且输出格式为 HTML（带嵌入式或外部资源）时有效。默认情况下此功能已禁用（false）。仅在明确了解原因并确定需要时才开启此选项。开启此选项会增加文档处理时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fixLinkIssue | boolean | 如果应修复该问题则为 true，否则为 false。 |

### isAnalyzeFonts() {#isAnalyzeFonts--}
```
public boolean isAnalyzeFonts()
```


根据需要替换字体，以确保文本中的所有字符均可显示。

**Returns:**
boolean
### setAnalyzeFonts(boolean analyzeFonts) {#setAnalyzeFonts-boolean-}
```
public void setAnalyzeFonts(boolean analyzeFonts)
```


根据需要替换字体，以确保文本中的所有字符均可显示。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| analyzeFonts | boolean | 如果应显示字体则为 true，否则为 false。 |

### isDisableFontLicenseVerifications() {#isDisableFontLicenseVerifications--}
```
public boolean isDisableFontLicenseVerifications()
```


禁用当前 XPS/OXPS 文档中所有字体的任何许可限制。

如果这些操作被该字体的许可证禁止，则许多字体相关操作无法执行。例如，如果许可证规则禁止嵌入，则某些字体无法嵌入到 PDF 文档中。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担所有可能的许可证/法律违规责任，即自行承担风险。强烈建议仅在完全确信不会侵犯版权法时才使用此标志。默认值为 false。代码示例请参见 [documentation][].

示例用法：

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Returns:**
boolean
### setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications) {#setDisableFontLicenseVerifications-boolean-}
```
public void setDisableFontLicenseVerifications(boolean disableFontLicenseVerifications)
```


设置标志以禁用当前 XPS/OXPS 文档中所有字体的任何许可证限制。

如果这些操作被该字体的许可证禁止，则许多字体相关操作无法执行。例如，如果许可证规则禁止嵌入，则某些字体无法嵌入到 PDF 文档中。使用此标志时请谨慎。设置后意味着设置此标志的人自行承担所有可能的许可证/法律违规责任，即自行承担风险。强烈建议仅在完全确信不会侵犯版权法时才使用此标志。默认值为 false。代码示例请参见 [documentation][].

示例用法：

```

 try (Viewer viewer = new Viewer("resume.oxps")) {
     HtmlViewOptions options = HtmlViewOptions.forEmbeddedResources("result.html");
     options.getPdfOptions().setDisableFontLicenseVerifications(true);
     viewer.view(options);
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/java/render-pdf-documents/#skip-font-license-verification-when-rendering-xps-and-oxps-files

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| disableFontLicenseVerifications | boolean |  |

