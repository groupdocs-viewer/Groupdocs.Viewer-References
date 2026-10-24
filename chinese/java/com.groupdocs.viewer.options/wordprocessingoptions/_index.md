---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Java API 参考"
description: "提供用于渲染文字处理文档的选项。"
type: docs
weight: 38
url: /zh/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

提供用于渲染文字处理文档的选项。


WordProcessingOptions 类提供用于渲染文字处理文档的选项
在 GroupDocs.Viewer 组件中。它封装了可用于的设置和参数
以控制文字处理文件的渲染过程和输出格式。
有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/)。


示例用法：

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | 初始化一个新的实例 |
WordProcessingOptions
类。
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | 检索用于渲染 HTM 和 HTML 文件的页面大小。 |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 设置用于渲染 HTM 和 HTML 文件的页面大小。 |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | 指示是否启用已跟踪更改（修订）的渲染。 |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | 设置是否启用已跟踪更改（修订）的渲染。 |
|
|  | [getLeftMargin()](#getLeftMargin--) | 检索 HTML 渲染的左页边距。 |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | 设置 HTML 渲染的左页边距。 |
|
|  | [getRightMargin()](#getRightMargin--) | 获取 HTML 渲染的右页边距。 |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | 设置 HTML 渲染的右页边距。 |
|
|  | [getTopMargin()](#getTopMargin--) | 检索 HTML 渲染的顶部页边距。 |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | 设置 HTML 渲染的顶部页边距。 |
|
|  | [getBottomMargin()](#getBottomMargin--) | 底部页边距（仅用于 HTML 渲染） |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | 设置 HTML 渲染的底部页边距。 |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | 此选项在渲染阿拉伯语、希伯来语、印度文字、基于拉丁字母或基于西里尔字母的脚本时启用字距调整和其他 OpenType 功能。 |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | 此选项在渲染阿拉伯语、希伯来语、印度文字、基于拉丁字母或基于西里尔字母的脚本时启用字距调整和其他 OpenType 功能。 |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | 指示在渲染为 HTML 或 PDF 时是否应禁用目录导航。 |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | 设置在渲染为 HTML 或 PDF 时是否禁用目录导航。 |
|
|  | [isUpdateFields()](#isUpdateFields--) | 获取一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前是否应更新某些类型的字段。 |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 设置一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前是否应更新某些类型的字段。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 获取生成图像的水平分辨率（每英寸点数）。 |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | 设置生成图像的水平分辨率（每英寸点数）。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 获取生成图像的垂直分辨率（每英寸点数）。 |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | 设置生成图像的垂直分辨率（每英寸点数）。 |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | 允许强制为加载的 WordProcessing 文档应用页码。 |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | 允许强制为加载的 WordProcessing 文档应用页码。 |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | 检查选项是否已更改。 |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


初始化一个新的实例
WordProcessingOptions
类。
包含用于渲染文字处理文档的选项。详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)。


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


检索用于渲染 HTM 和 HTML 文件的页面大小。


使用默认页面尺寸时，某些内容可能无法适应页面框架。
为了适应内容，您可以使用[PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3)设置更大的页面尺寸，例如 A3。


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


设置用于渲染 HTM 和 HTML 文件的页面大小。


使用默认页面尺寸时，某些内容可能无法适应页面框架。
为了适应内容，您可以使用[PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3)设置更大的页面尺寸，例如 A3。


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 输出页面的尺寸。 |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


指示是否启用已跟踪更改（修订）的渲染。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)。


**Returns:**
boolean -  true  如果已启用已跟踪更改的渲染，  false  否则。

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


设置是否启用已跟踪更改（修订）的渲染。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | 值 | boolean | true  启用已跟踪更改的渲染，  false  禁用它。 |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


检索 HTML 渲染的左页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Returns:**
java.lang.Double - 左页边距值。

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


设置 HTML 渲染的左页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | 要设置的左页边距值。 |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


获取 HTML 渲染的右页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Returns:**
java.lang.Double - 右页边距的值。

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


设置 HTML 渲染的右页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | 要设置的右页边距值。 |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


检索 HTML 渲染的顶部页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Returns:**
java.lang.Double - 顶部页边距。

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


设置 HTML 渲染的顶部页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | topMargin | java.lang.Double | 要设置的顶部页边距。 |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


底部页边距（仅用于 HTML 渲染）
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Returns:**
java.lang.Double - 底部页边距。

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


设置 HTML 渲染的底部页边距。
详情请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | 要设置的底部页边距。 |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


此选项在渲染阿拉伯语、希伯来语、印度文字、基于拉丁字母或基于西里尔字母的脚本时启用字距调整和其他 OpenType 功能。


**Returns:**
boolean - 如果启用了 OpenType 功能则为 True，否则为 false。

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


此选项在渲染阿拉伯语、希伯来语、印度文字、基于拉丁字母或基于西里尔字母的脚本时启用字距调整和其他 OpenType 功能。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | True 表示启用 OpenType 功能，false 表示不启用。 |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


指示在渲染为 HTML 或 PDF 时是否应禁用目录导航。若将此选项设为 true，HTML 渲染时，目录中的相对链接将被 span 标签替代，功能被移除但保持视觉外观。PDF 渲染时，目录将以纯文本形式呈现，不包含链接。


**Returns:**
boolean - 如果目录导航被禁用则为 True；否则为 false。

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


设置在渲染为 HTML 或 PDF 时是否应禁用目录导航。若将此选项设为 true，HTML 渲染时，目录中的相对链接将被 span 标签替代，功能被移除但保持视觉外观。PDF 渲染时，目录将以纯文本形式呈现，不包含链接。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | 指示是否应禁用目录导航。 |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


获取一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前，是否应更新某些类型的字段。此属性的默认值为 true \\u2014 保存前将更新字段。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)。


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


设置一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前，是否应更新某些类型的字段。此属性的默认值为 true \\u2014 保存前将更新字段。


有关详细信息，请参阅[文档](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving)。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


获取生成图像的水平分辨率（以每英寸点数计）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Returns:**
int - 水平分辨率（单位为 DPI）。

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


设置生成图像的水平分辨率（以每英寸点数计）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | horizontalResolution | int | 水平分辨率（单位为 DPI）。 |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


获取生成图像的垂直分辨率（以每英寸点数计）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Returns:**
int - 垂直分辨率（单位为 DPI）。

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


设置生成图像的垂直分辨率（以每英寸点数计）。此选项仅在将 WordProcessing 文档渲染为 PNG 或 JPEG 格式时使用。


默认值为 96 DPI。最小可能值为 72 DPI，最大可能值为 600 DPI。
如果用户指定的值超出这些限制，将使用最小或最大可能值。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | verticalResolution | int | 垂直分辨率（单位为 DPI）。 |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


允许强制为加载的 WordProcessing 文档应用页码。默认情况下为 [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 文档保持完整。


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


允许强制为加载的 WordProcessing 文档应用页码。默认情况下为 [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 文档保持完整。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | 页码位置。 |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查选项是否已更改。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | o | java.lang.Object | 用于比较相等性的对象。 |
|

**Returns:**
boolean -  true  如果选项等于指定对象，则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```


计算此对象的哈希码值。哈希码基于
对象的内部状态，并用于基于哈希的数据结构
例如哈希映射和哈希集合。
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - 此对象的哈希码值。

