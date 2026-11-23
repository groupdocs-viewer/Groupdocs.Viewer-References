---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "使用此类指定要应用于输出 PDF 文件的 PDF 优化选项。"
type: docs
weight: 21
url: /zh/java/com.groupdocs.viewer.options/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class PdfOptimizationOptions
```

使用此类指定要应用于输出 PDF 文件的 PDF 优化选项。


这些优化选项支持所有可导出为 PDF 的输入文件格式。
有关详细信息和代码示例，请参阅此 [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) 及其子页面。


示例用法：

````

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
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | 将 MaxResolution 选项的默认值设置为 300，ImageQuality 选项的默认值设置为 100。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [isLinearize()](#isLinearize--) | 启用对输出 PDF 文件的优化，以便在网页浏览器中在线查看。 |
|
|  | [setLinearize(boolean linearize)](#setLinearize-boolean-) | 设置是否对输出 PDF 进行优化，以便在网页浏览器中在线浏览。 |
|
|  | [isRemoveAnnotations()](#isRemoveAnnotations--) | 当注释不必要时可以删除它们。 |
|
|  | [setRemoveAnnotations(boolean removeAnnotations)](#setRemoveAnnotations-boolean-) | 设置是否从 PDF 中删除不必要的注释。 |
|
|  | [isRemoveFormFields()](#isRemoveFormFields--) | 如果 PDF 文档包含 AcroForms，我们可以尝试通过展平表单字段来减小文件大小。 |
|
|  | [setRemoveFormFields(boolean removeFormFields)](#setRemoveFormFields-boolean-) | 设置是否从 PDF 中删除表单字段。 |
|
|  | [isConvertToGrayScale()](#isConvertToGrayScale--) | PDF 文件由文本、图像、附件、注释、图形和其他对象组成。 |
|
|  | [setConvertToGrayScale(boolean convertToGrayScale)](#setConvertToGrayScale-boolean-) | 设置是否将 PDF 转换为灰度。 |
|
|  | [isSubsetFonts()](#isSubsetFonts--) | 页面上用于显示文本的每种字体都包含字符的字形集合。 |
|
|  | [setSubsetFonts(boolean subsetFonts)](#setSubsetFonts-boolean-) | 设置是否对 PDF 中的字体进行子集化。 |
|
|  | [isCompressImages()](#isCompressImages--) | 如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。 |
|
|  | [setCompressImages(boolean compressImages)](#setCompressImages-boolean-) | 设置是否压缩 PDF 中的图像。 |
|
|  | [getImageQuality()](#getImageQuality--) | 如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。 |
|
|  | [setImageQuality(int imageQuality)](#setImageQuality-int-) | 设置压缩 PDF 中图像的图像质量。 |
|
|  | [isResizeImages()](#isResizeImages--) | 可与 CompressImages 选项一起使用，以较低的分辨率调整图像大小。 |
|
|  | [setResizeImages(boolean resizeImages)](#setResizeImages-boolean-) | 设置是否在 PDF 中调整图像大小。 |
|
|  | [getMaxResolution()](#getMaxResolution--) | 可与 CompressImages 选项一起使用，以较低的分辨率调整图像大小。 |
|
|  | [setMaxResolution(int maxResolution)](#setMaxResolution-int-) | 设置在 PDF 中调整图像大小的最大分辨率。 |
|
|  | [isOptimizeSpreadsheets()](#isOptimizeSpreadsheets--) | 优化 Excel 电子表格的边框线和字体，以获得更小的输出文件大小。 |
|
|  | [setOptimizeSpreadsheets(boolean optimizeSpreadsheets)](#setOptimizeSpreadsheets-boolean-) | 设置是否在 PDF 中优化电子表格。 |
|
|  | [isRemovePrivateInfo()](#isRemovePrivateInfo--) | 如果设置为 true，则删除私人信息（页面片段信息）。 |
|
|  | [setRemovePrivateInfo(boolean removePrivateInfo)](#setRemovePrivateInfo-boolean-) | 设置是否从 PDF 中删除私人信息。 |
|
|  | [isUnembedFonts()](#isUnembedFonts--) | 如果文档使用嵌入字体，这意味着所有字体数据都嵌入在文档中。 |
|
|  | [setUnembedFonts(boolean unembedFonts)](#setUnembedFonts-boolean-) | 设置是否在 PDF 中取消嵌入嵌入的字体。 |
|
|  | [isLinkDuplicateStreams()](#isLinkDuplicateStreams--) | 有时文档包含多个相同的资源流（例如图像）。 |
|
|  | [setLinkDuplicateStreams(boolean linkDuplicateStreams)](#setLinkDuplicateStreams-boolean-) | 设置是否在 PDF 中链接重复的流。 |
|
|  | [isAllowReusePageContent()](#isAllowReusePageContent--) | 如果此属性设置为 true，在为相同页面优化文档时，页面内容将被重复使用。 |
|
|  | [setAllowReusePageContent(boolean allowReusePageContent)](#setAllowReusePageContent-boolean-) | 设置是否允许在 PDF 中重复使用页面内容。 |
|
|  | [isRemoveUnusedStreams()](#isRemoveUnusedStreams--) | 有时文档包含未使用的资源流。 |
|
|  | [setRemoveUnusedStreams(boolean removeUnusedStreams)](#setRemoveUnusedStreams-boolean-) | 设置是否从 PDF 中删除未使用的流。 |
|
|  | [isRemoveUnusedObjects()](#isRemoveUnusedObjects--) | PDF 文档有时包含未被引用的 PDF 对象 |
来自文档中的任何其他对象。
|
|  | [setRemoveUnusedObjects(boolean removeUnusedObjects)](#setRemoveUnusedObjects-boolean-) | 设置是否从 PDF 中删除未使用的对象。 |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


将 MaxResolution 选项的默认值设置为 300，ImageQuality 选项的默认值设置为 100。


有关详细信息和代码示例，请参阅此 [page](../https://docs.groupdocs.com/viewer/java/optimization-pdf-options/) 及其子页面。


### isLinearize() {#isLinearize--}
```
public boolean isLinearize()
```


启用对输出 PDF 文件的优化，以便在网页浏览器中在线查看。


代码示例请参见此 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)。


**Returns:**
boolean -  true  如果输出 PDF 已针对在线浏览进行优化，则为 true；否则为 false。

### setLinearize(boolean linearize) {#setLinearize-boolean-}
```
public void setLinearize(boolean linearize)
```


设置是否对输出 PDF 进行优化，以便在网页浏览器中在线浏览。


代码示例请参见此 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-for-web/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | linearize | boolean | true  将输出 PDF 优化用于在线浏览；false 则相反。 |
|

### isRemoveAnnotations() {#isRemoveAnnotations--}
```
public boolean isRemoveAnnotations()
```


当注释不必要时可以删除它们。若需要但不需要额外编辑，则可以将其扁平化。这将减小文件大小。


***Note:** The default value is 
false
.*
代码示例请参见此 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)。


**Returns:**
boolean -  true  如果注释被删除，则为 true；否则为 false。

### setRemoveAnnotations(boolean removeAnnotations) {#setRemoveAnnotations-boolean-}
```
public void setRemoveAnnotations(boolean removeAnnotations)
```


设置是否从 PDF 中删除不必要的注释。


***Note:** The default value is 
false
.*
代码示例请参见此 [documentation](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-annotations/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | removeAnnotations | boolean | true 以移除不必要的批注， false 否则。 |
|

### isRemoveFormFields() {#isRemoveFormFields--}
```
public boolean isRemoveFormFields()
```


如果 PDF 文档包含 AcroForms，我们可以尝试通过展平表单字段来减小文件大小。


***Note:** The default value is 
false
.*
有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)。


**Returns:**
boolean - true 如果表单字段已被移除， false 否则。

### setRemoveFormFields(boolean removeFormFields) {#setRemoveFormFields-boolean-}
```
public void setRemoveFormFields(boolean removeFormFields)
```


设置是否从 PDF 中删除表单字段。


***Note:** The default value is 
false
.*
有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-remove-fields/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | removeFormFields | boolean | true 以移除表单字段， false 否则。 |
|

### isConvertToGrayScale() {#isConvertToGrayScale--}
```
public boolean isConvertToGrayScale()
```


PDF 文件由文本、图像、附件、注释、图形和其他对象组成。
您可能会遇到需要将 PDF 从 RGB 色彩空间转换为灰度的需求，以便在打印这些 PDF 文件时更快。
此外，当文件被转换为灰度时，文档的大小也会减小，但此更改可能导致文档质量下降。
目前，此功能由 Adobe Acrobat 的预检功能支持。


***Note:** The default value is 
false
.*
有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)。


**Returns:**
boolean - true 如果 PDF 已转换为灰度， false 否则。

### setConvertToGrayScale(boolean convertToGrayScale) {#setConvertToGrayScale-boolean-}
```
public void setConvertToGrayScale(boolean convertToGrayScale)
```


设置是否将 PDF 转换为灰度。


***Note:** The default value is 
false
.*
有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-convert-grayscale/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | convertToGrayScale | boolean | true 以将 PDF 转换为灰度， false 否则。 |
|

### isSubsetFonts() {#isSubsetFonts--}
```
public boolean isSubsetFonts()
```


页面上用于显示文本的每种字体都包含字符的字形集合。
PDF 规范支持“字体子集”，即仅包含已使用字形的字体。
当需要更新文本时（因为可能缺少所需字形），这可能会导致问题，但对于不打算更改的文档，这可以减小尺寸。


***Note:** The default value is 
false
.*
如果文件使用嵌入式字体，则包含所有字体数据。GroupDocs.Viewer 可以对嵌入式字体进行子集化以减小文件大小。有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)。


**Returns:**
boolean - true 如果字体已进行子集化， false 否则。

### setSubsetFonts(boolean subsetFonts) {#setSubsetFonts-boolean-}
```
public void setSubsetFonts(boolean subsetFonts)
```


设置是否对 PDF 中的字体进行子集化。


***Note:** The default value is 
false
.*
如果文件使用嵌入式字体，则包含所有字体数据。GroupDocs.Viewer 可以对嵌入式字体进行子集化以减小文件大小。有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-subset-fonts/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | subsetFonts | boolean | true 以对子集化字体， false 否则。 |
|

### isCompressImages() {#isCompressImages--}
```
public boolean isCompressImages()
```


如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。
为了启用图像压缩，请将此选项设置为 true。文档中的所有图像将被重新压缩。
压缩由 ImageQuality 属性定义，该属性是以百分比表示的质量值。
100% 表示质量不变。要降低图像质量，请将 ImageQuality 属性设置为低于 100。


***Note:** The default value is 
false
.*
使用此选项可启用其他压缩选项：#setImageQuality(int).setImageQuality(int) 等。有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)。


**Returns:**
boolean - true 如果图像已压缩， false 否则。

### setCompressImages(boolean compressImages) {#setCompressImages-boolean-}
```
public void setCompressImages(boolean compressImages)
```


设置是否压缩 PDF 中的图像。


***Note:** The default value is 
false
.*
使用此选项可启用其他压缩选项：#setImageQuality(int).setImageQuality(int) 等。有关代码示例，请参阅此[文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | compressImages | boolean | true 以压缩图像， false 否则。 |
|

### getImageQuality() {#getImageQuality--}
```
public int getImageQuality()
```


如果源 PDF 文件包含图像，请考虑压缩图像并设置其质量。为了启用图像压缩，请将 CompressImages 选项设置为 true。文档中的所有图像将被重新压缩。压缩由 ImageQuality 属性定义，该属性表示质量的百分比值。100% 表示质量不变。要降低图像质量，请将 CompressImages 选项设置为 true 并将 ImageQuality 属性设置为小于 100。

<br />


***Note:** The default value is 
100
.*
要更改图像质量，首先将 #setCompressImages(boolean).setCompressImages(boolean) 属性设置为 true。代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)。


**Returns:**
int - 图像质量（值在 1 到 100 之间）。

### setImageQuality(int imageQuality) {#setImageQuality-int-}
```
public void setImageQuality(int imageQuality)
```


设置压缩 PDF 中图像的图像质量。


***Note:** The default value is 
100
.*
要更改图像质量，首先将 #setCompressImages(boolean).setCompressImages(boolean) 属性设置为 true。代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-reduce-image-quality/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | imageQuality | int | 图像质量（值在 1 到 100 之间）。 |
|

### isResizeImages() {#isResizeImages--}
```
public boolean isResizeImages()
```


可与 CompressImages 选项一起使用，以较低的分辨率调整图像大小。
在这种情况下，我们应将 CompressImage 设置为 true，ResizeImages 设置为 true，并将 MaxResolution 设置为适当的值。


***Note:** The default value is 
false
.*
要启用此选项，请将属性设置为 true。此选项允许设置该属性。代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)。


**Returns:**
boolean -  true  如果图像已调整大小，  false  否则。

### setResizeImages(boolean resizeImages) {#setResizeImages-boolean-}
```
public void setResizeImages(boolean resizeImages)
```


设置是否在 PDF 中调整图像大小。


***Note:** The default value is 
false
.*
要启用此选项，请将属性设置为 true。此选项允许设置该属性。代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | resizeImages | boolean | true  用于调整图像大小，  false  否则。 |
|

### getMaxResolution() {#getMaxResolution--}
```
public int getMaxResolution()
```


可与 CompressImages 选项一起使用，以较低分辨率调整图像大小。在这种情况下，我们应将 CompressImage 设置为 true，ResizeImages 设置为 true，并将 MaxResolution 设置为适当的值。


***Note:** The default value is 
300
.*
要启用此选项，请将 #setCompressImages(boolean).setCompressImages(boolean) 和 #setMaxResolution(int).setMaxResolution(int) 属性设置为 true。
代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)。


**Returns:**
int - 图像的最大分辨率。

### setMaxResolution(int maxResolution) {#setMaxResolution-int-}
```
public void setMaxResolution(int maxResolution)
```


设置在 PDF 中调整图像大小的最大分辨率。


***Note:** The default value is 
300
.*
要启用此选项，请将 #setCompressImages(boolean).setCompressImages(boolean) 和 #setMaxResolution(int).setMaxResolution(int) 属性设置为 true。
代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-set-max-resolution/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | maxResolution | int | 图像的最大分辨率。 |
|

### isOptimizeSpreadsheets() {#isOptimizeSpreadsheets--}
```
public boolean isOptimizeSpreadsheets()
```


优化 Excel 电子表格的边框线和字体，以获得更小的输出文件大小。


*The output PDF will not include embedded Arial and Times New Roman fonts with characters 32-127.*


***Note:** The default value is 
false
.*
代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)。


**Returns:**
boolean -  true  如果电子表格已优化，  false  否则。

### setOptimizeSpreadsheets(boolean optimizeSpreadsheets) {#setOptimizeSpreadsheets-boolean-}
```
public void setOptimizeSpreadsheets(boolean optimizeSpreadsheets)
```


设置是否在 PDF 中优化电子表格。


代码示例请参阅此 [文档](../https://docs.groupdocs.com/viewer/java/optimization-pdf-spreadsheets/)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | optimizeSpreadsheets | boolean | true  用于优化电子表格，  false  否则。 |
|

### isRemovePrivateInfo() {#isRemovePrivateInfo--}
```
public boolean isRemovePrivateInfo()
```


如果设置为 true，则删除私人信息（页面片段信息）。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  如果已删除私人信息，  false  否则。

### setRemovePrivateInfo(boolean removePrivateInfo) {#setRemovePrivateInfo-boolean-}
```
public void setRemovePrivateInfo(boolean removePrivateInfo)
```


设置是否从 PDF 中删除私人信息。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | removePrivateInfo | boolean | true  用于删除私人信息，  false  否则。 |
|

### isUnembedFonts() {#isUnembedFonts--}
```
public boolean isUnembedFonts()
```


如果文档使用嵌入字体，这意味着所有字体数据都嵌入在文档中。
优势在于无论用户\\u2019s机器上是否安装了该字体，文档都可以查看。但嵌入字体会使文档体积增大。
unembed fonts 方法会移除所有已嵌入的字体。这会减小文档大小，但如果未安装正确的字体，文档可能会变得无法阅读。


***Note:** The default value is 
false
.*


**Returns:**
布尔值 -  true  如果已嵌入的字体已被取消嵌入，则为 true， false 表示否则。

### setUnembedFonts(boolean unembedFonts) {#setUnembedFonts-boolean-}
```
public void setUnembedFonts(boolean unembedFonts)
```


设置是否在 PDF 中取消嵌入嵌入的字体。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | unembedFonts | boolean | true  表示取消嵌入已嵌入的字体， false 表示否则。 |
|

### isLinkDuplicateStreams() {#isLinkDuplicateStreams--}
```
public boolean isLinkDuplicateStreams()
```


有时文档包含多个相同的资源流（例如图像）。
例如，当文档与自身拼接时可能会发生这种情况。
输出文档包含同一资源流的两个独立副本。
我们会分析并比较所有资源流。如果流出现重复，则将其合并，即只保留一个副本，适当地更改引用并删除对象的复制品。
有时这会减小文档大小。


***Note:** The default value is 
false
.*


**Returns:**
布尔值 -  true  表示重复的流已被链接， false 表示否则。

### setLinkDuplicateStreams(boolean linkDuplicateStreams) {#setLinkDuplicateStreams-boolean-}
```
public void setLinkDuplicateStreams(boolean linkDuplicateStreams)
```


设置是否在 PDF 中链接重复的流。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | linkDuplicateStreams | boolean | true  表示链接重复的流， false 表示否则。 |
|

### isAllowReusePageContent() {#isAllowReusePageContent--}
```
public boolean isAllowReusePageContent()
```


如果此属性设置为 true，在为相同页面优化文档时，页面内容将被重复使用。


***Note:** The default value is 
false
.*


**Returns:**
布尔值 -  true  表示页面内容被复用， false 表示否则。

### setAllowReusePageContent(boolean allowReusePageContent) {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean allowReusePageContent)
```


设置是否允许在 PDF 中重复使用页面内容。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | allowReusePageContent | boolean | true  表示允许复用页面内容， false 表示否则。 |
|

### isRemoveUnusedStreams() {#isRemoveUnusedStreams--}
```
public boolean isRemoveUnusedStreams()
```


有时文档包含未使用的资源流。
这些流不是\\u201cunused objects\\u201d，因为它们是从页面\\u2019s资源字典中引用的。
当图像已从页面中移除但未从页面资源中移除时，可能会出现这种情况。
此外，当从文档中提取页面且文档页面拥有\\u201ccommon\\u201d资源时，这种情况经常出现，
即相同的 Resources 对象。会分析页面内容以确定资源流
是否被使用。未使用的流将被移除。有时这会减小文档大小。


***Note:** The default value is 
false
.*


**Returns:**
布尔值 -  true  表示未使用的流已被移除， false 表示否则。

### setRemoveUnusedStreams(boolean removeUnusedStreams) {#setRemoveUnusedStreams-boolean-}
```
public void setRemoveUnusedStreams(boolean removeUnusedStreams)
```


设置是否从 PDF 中删除未使用的流。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | removeUnusedStreams | boolean | true  表示移除未使用的流， false 表示否则。 |
|

### isRemoveUnusedObjects() {#isRemoveUnusedObjects--}
```
public boolean isRemoveUnusedObjects()
```


PDF 文档有时包含未被引用的 PDF 对象
来自文档中的任何其他对象。例如，这种情况可能会发生，
当页面从文档页面树中被移除，但页面对象本身 isn\\u2019t 被移除。
删除这些对象不会使文档无效，而是会使其变小。


***Note:** The default value is 
false
.*


**Returns:**
boolean -  true  如果未使用的对象已被删除，则为 true，  false  否则。

### setRemoveUnusedObjects(boolean removeUnusedObjects) {#setRemoveUnusedObjects-boolean-}
```
public void setRemoveUnusedObjects(boolean removeUnusedObjects)
```


设置是否从 PDF 中删除未使用的对象。


***Note:** The default value is 
false
.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | removeUnusedObjects | boolean | true  表示删除未使用的对象，  false  表示不删除。 |
|

