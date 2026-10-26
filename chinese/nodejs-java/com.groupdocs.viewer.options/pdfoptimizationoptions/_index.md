---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "使用此类指定要应用于输出 PDF 文件的 PDF 优化选项。"
type: docs
weight: 21
url: /zh/nodejs-java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

使用此类指定要应用于输出 PDF 文件的 PDF 优化选项。

这些优化选项支持所有可导出为 PDF 的输入文件格式。有关详细信息和代码示例，请参阅此 [page][] 及其子页面。

示例用法：

```

 try (Viewer viewer = new Viewer("sample.docx")) {
     PdfViewOptions viewOptions = new PdfViewOptions();
     viewOptions.setPdfOptimizationOptions(new PdfOptimizationOptions());
     viewOptions.getPdfOptimizationOptions().setLinearize(true);
     viewOptions.getPdfOptimizationOptions().setRemoveAnnotations(true);
     viewOptions.getPdfOptimizationOptions().setRemoveFormFields(true);
     viewOptions.getPdfOptimizationOptions().setConvertToGrayScale(true);
     viewOptions.getPdfOptimizationOptions().setSubsetFonts(true);
     viewOptions.getPdfOptimizationOptions().setCompressImages(true);
     viewOptions.getPdfOptimizationOptions().setImageQuality(50);
     viewOptions.getPdfOptimizationOptions().setResizeImages(true);
     viewOptions.getPdfOptimizationOptions().setMaxResolution(50);
     viewOptions.getPdfOptimizationOptions().setRemovePrivateInfo(true);
     viewOptions.getPdfOptimizationOptions().setUnembedFonts(true);
     viewOptions.getPdfOptimizationOptions().setLinkDuplicateStreams(true);
     viewOptions.getPdfOptimizationOptions().setAllowReusePageContent(true);

     viewer.view(viewOptions);
 }
 
```


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | 将 MaxResolution 选项的默认值设置为 300，ImageQuality 选项的默认值设置为 100。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isLinearize()](#isLinearize--) | 启用对输出 PDF 文件的优化，以便在网页浏览器中在线查看。 |
| [setLinearize(boolean linearize)](#setLinearize-boolean-) | 设置是否对输出 PDF 进行优化，以便在网页浏览器中在线浏览。 |
| [isRemoveAnnotations()](#isRemoveAnnotations--) | 当注释不必要时可以删除它们。 |
| [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | 设置是否从 PDF 中移除不必要的注释。 |
| [isRemoveFormFields()](#isRemoveFormFields--) | 如果 PDF 文档包含 AcroForms，我们可以尝试通过展平表单字段来减小文件大小。 |
| [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | 设置是否从 PDF 中移除表单字段。 |
| [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF 文件由文本、图像、附件、注释、图形和其他对象组成。 |
| [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | 设置是否将 PDF 转换为灰度。 |
| [isSubsetFonts()](#isSubsetFonts--) | 页面上用于显示文本的每种字体都包含字符字形集合。 |
| [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | 设置是否对 PDF 中的字体进行子集化。 |
| [isCompressImages()](#isCompressImages--) | 如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。 |
| [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | 设置是否压缩 PDF 中的图像。 |
| [getImageQuality()](#getImageQuality--) | 如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。 |
| [setImageQuality(int imageQuality)](#setImageQuality-int-) | 设置压缩 PDF 中图像的图像质量。 |
| [isResizeImages()](#isResizeImages--) | 可与 CompressImages 选项一起使用，以较低分辨率调整图像大小。 |
| [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | 设置是否调整 PDF 中图像的大小。 |
| [getMaxResolution()](#getMaxResolution--) | 可与 CompressImages 选项一起使用，以较低分辨率调整图像大小。 |
| [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | 设置 PDF 中图像调整大小的最大分辨率。 |
| [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | 优化 Excel 电子表格的边框线和字体，以获得更小的输出文件大小。 |
| [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | 设置是否优化 PDF 中的电子表格。 |
| [isRemovePrivateInfo()](#isRemovePrivateInfo--) | 如果设置为 true，则移除私人信息（页面片段信息）。 |
| [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | 设置是否从 PDF 中移除私人信息。 |
| [isUnembedFonts()](#isUnembedFonts--) | 如果文档使用嵌入式字体，则意味着所有字体数据都嵌入在文档中。 |
| [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | 设置是否在 PDF 中取消嵌入嵌入式字体。 |
| [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | 有时文档包含多个相同的资源流（例如图像）。 |
| [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | 设置是否在 PDF 中链接重复的流。 |
| [isAllowReusePageContent()](#isAllowReusePageContent--) | 如果此属性设置为 true，则在对相同页面进行优化时，将重用页面内容。 |
| [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | 设置是否允许在 PDF 中重复使用页面内容。 |
| [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | 有时文档会包含未使用的资源流。 |
| [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | 设置是否从 PDF 中移除未使用的流。 |
| [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF 文档有时会包含未被文档中其他对象引用的 PDF 对象。 |
| [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | 设置是否从 PDF 中移除未使用的对象。 |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


将 MaxResolution 选项的默认值设置为 300，ImageQuality 选项的默认值设置为 100。

有关详细信息和代码示例，请参阅此 [page][] 及其子页面。


[page]: https://docs.groupdocs.com/viewer/java/optimization-pdf-options/

### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


启用对输出 PDF 文件的优化，以便在网页浏览器中在线查看。

代码示例请参阅此 [documentation][]。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Returns:**
boolean -  true  如果输出的 PDF 已针对在线浏览进行优化，  false  否则。
### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


设置是否对输出 PDF 进行优化，以便在网页浏览器中在线浏览。

代码示例请参阅此 [documentation][]。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linearize | boolean | true  用于优化输出的 PDF 以进行在线浏览，  false  否则。 |

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


当注释不必要时可以删除它们。若需要注释但不需要额外编辑，则可以将其扁平化。这将减小文件大小。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Returns:**
boolean -  true  如果注释被删除，  false  否则。
### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


设置是否从 PDF 中移除不必要的注释。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeAnnotations | boolean | true  用于删除不必要的注释，  false  否则。 |

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


如果 PDF 文档包含 AcroForms，我们可以尝试通过展平表单字段来减小文件大小。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Returns:**
boolean -  true  如果表单字段被删除，  false  否则。
### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


设置是否从 PDF 中移除表单字段。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeFormFields | boolean | true  用于删除表单字段，  false  否则。 |

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF 文件由文本、图像、附件、注释、图形和其他对象组成。您可能会遇到需要将 PDF 从 RGB 色彩空间转换为灰度的需求，以便在打印这些 PDF 文件时更快。同时，文件转换为灰度后，文档大小也会减小，但此更改可能导致文档质量下降。目前，此功能由 Adobe Acrobat 的 Pre-Flight 功能支持。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Returns:**
boolean -  true  如果 PDF 已转换为灰度，  false  否则。
### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


设置是否将 PDF 转换为灰度。

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertToGrayScale | boolean | true  用于将 PDF 转换为灰度，  false  否则。 |

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


页面上用于显示文本的每种字体都包含一套字符字形。PDF 规范支持"font subset"（即仅包含已使用字形的字体）。这可能在需要更新文本时导致问题（因为可能缺少所需的字形），但对于不打算更改的文档，这可以减小体积。

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Returns:**
boolean -  true  如果字体已进行子集化，  false  否则。
### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


设置是否对 PDF 中的字体进行子集化。

***Note:** The default value is  false .* If the file uses embedded fonts, it contains all font data. GroupDocs.Viewer can subset embedded fonts to reduce the file size. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| subsetFonts | boolean | true  用于对字体进行子集化，  false  否则。 |

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。要启用图像压缩，请将此选项设为 true。文档中的所有图像将重新压缩。压缩由 ImageQuality 属性定义，该属性是质量的百分比值。100% 表示质量不变。要降低图像质量，请将 ImageQuality 属性设置为小于 100。

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
boolean -  true  如果图像已压缩，  false  否则。
### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


设置是否压缩 PDF 中的图像。

***Note:** The default value is  false .* Use this option to allow other compressing options: \#setImageQuality(int).setImageQuality(int) and . For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| compressImages | boolean | true  用于压缩图像，  false  否则。 |

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。要启用图像压缩，请将 CompressImages 选项设为 true。文档中的所有图像将重新压缩。压缩由 ImageQuality 属性定义，该属性是质量的百分比值。100% 表示质量不变。要降低图像质量，请将 CompressImages 选项设为 true 并将 ImageQuality 属性设置为小于 100。

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Returns:**
int - 图像质量（值在 1 到 100 之间）。
### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


设置压缩 PDF 中图像的图像质量。

***Note:** The default value is  100 .* To change the image quality, first set the \#setCompressImages(boolean).setCompressImages(boolean) property to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageQuality | int | 图像质量（值在 1 到 100 之间）。 |

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


可与 CompressImages 选项一起使用，以较低分辨率调整图像大小。在这种情况下，我们应将 CompressImage 设为 true，ResizeImages 设为 true，并将 MaxResolution 设置为适当的值。

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
boolean -  true  如果图像已调整大小，  false  否则。
### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


设置是否调整 PDF 中图像的大小。

***Note:** The default value is  false .* To allow this option, set the  property to true. This option allows setting the  property. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resizeImages | boolean | true  用于调整图像大小，  false  否则。 |

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


可与 CompressImages 选项一起使用，以较低分辨率调整图像大小。在这种情况下，我们应将 CompressImage 设为 true，ResizeImages 设为 true，并将 MaxResolution 设置为适当的值。

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Returns:**
int - 图像的最大分辨率。
### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


设置 PDF 中图像调整大小的最大分辨率。

***Note:** The default value is  300 .* To allow this option, set the \#setCompressImages(boolean).setCompressImages(boolean) and \#setMaxResolution(int).setMaxResolution(int) properties to true. For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxResolution | int | 图像的最大分辨率。 |

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


优化 Excel 电子表格的边框线和字体，以获得更小的输出文件大小。

*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*

***Note:** The default value is  false .* For code example, see this [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Returns:**
boolean -  true  如果电子表格已优化，  false  否则。
### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


设置是否优化 PDF 中的电子表格。

代码示例请参阅此 [documentation][]。


[documentation]: https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| optimizeSpreadsheets | boolean | true  用于优化电子表格，  false  否则。 |

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


如果设置为 true，则移除私人信息（页面片段信息）。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果已删除私人信息，  false  否则。
### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


设置是否从 PDF 中移除私人信息。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removePrivateInfo | boolean | true  用于删除私人信息，  false  否则。 |

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


如果文档使用嵌入字体，这意味着所有字体数据都放置在文档中。其优势在于无论用户的机器是否安装了该字体，文档都可以查看。但嵌入字体会使文档体积增大。unembed fonts 方法会移除所有嵌入的字体。这会减小文档大小，但如果未安装正确的字体，文档可能会变得无法阅读。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果嵌入的字体已被取消嵌入，  false  否则。
### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


设置是否在 PDF 中取消嵌入嵌入式字体。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unembedFonts | boolean | true  用于取消嵌入已嵌入的字体，  false  否则。 |

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


有时文档包含多个相同的资源流（例如图像）。这可能在文档与自身拼接时发生。输出文档包含两个相同资源流的独立副本。我们会分析所有资源流并进行比较。如果流被复制，它们会被合并，即只保留一个副本，引用会相应更改，对象的副本会被删除。有时这会减小文档大小。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果重复的流已链接，则为 true， false 否则。
### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


设置是否在 PDF 中链接重复的流。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| linkDuplicateStreams | boolean | true  用于链接重复的流， false 否则。 |

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


如果此属性设置为 true，则在对相同页面进行优化时，将重用页面内容。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果页面内容被复用，则为 true， false 否则。
### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


设置是否允许在 PDF 中重复使用页面内容。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| allowReusePageContent | boolean | true  用于允许复用页面内容， false 否则。 |

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


有时文档包含未使用的资源流。这些流不是“未使用的对象”，因为它们在页面的资源字典中被引用。这可能发生在图像已从页面移除但未从页面资源中移除的情况下。此外，当从文档中提取页面且文档页面具有“公共”资源，即相同的 Resources 对象时，这种情况也经常出现。会分析页面内容以确定资源流是否被使用。未使用的流将被删除。有时这会减小文档大小。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果未使用的流被删除，则为 true， false 否则。
### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


设置是否从 PDF 中移除未使用的流。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeUnusedStreams | boolean | true  用于删除未使用的流， false 否则。 |

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


有时 PDF 文档会包含未被文档中其他对象引用的 PDF 对象。例如，当页面从文档页面树中被移除，但页面对象本身未被删除时，就会出现这种情况。删除这些对象不会使文档无效，反而会使其体积变小。

***Note:** The default value is  false .*

**Returns:**
boolean -  true  如果未使用的对象被删除，则为 true， false 否则。
### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


设置是否从 PDF 中移除未使用的对象。

***Note:** The default value is  false .*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| removeUnusedObjects | boolean | true  用于删除未使用的对象， false 否则。 |

