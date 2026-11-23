---
title: "WordProcessingOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供渲染文字处理文档的选项。"
type: docs
weight: 38
url: /zh/nodejs-java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

提供渲染文字处理文档的选项。

WordProcessingOptions 类提供在 GroupDocs.Viewer 组件中渲染文字处理文档的选项。它封装了可用于控制渲染过程和文字处理文件输出格式的设置和参数。详情请参阅 [文档][].

示例用法：

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingOptions()](#WordProcessingOptions--) | 初始化 WordProcessingOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageSize()](#getPageSize--) | 检索用于渲染 HTM 和 HTML 文件的页面大小。 |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | 设置用于渲染 HTM 和 HTML 文件的页面大小。 |
| [isRenderTrackedChanges()](#isRenderTrackedChanges--) | 指示是否已启用对已跟踪更改（修订）的渲染。 |
| [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | 设置是否启用对已跟踪更改（修订）的渲染。 |
| [getLeftMargin()](#getLeftMargin--) | 检索 HTML 渲染的左页边距。 |
| [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | 设置 HTML 渲染的左页边距。 |
| [getRightMargin()](#getRightMargin--) | 获取 HTML 渲染的右页边距。 |
| [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | 设置 HTML 渲染的右页边距。 |
| [getTopMargin()](#getTopMargin--) | 检索 HTML 渲染的顶部页边距。 |
| [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | 设置 HTML 渲染的顶部页面边距。 |
| [getBottomMargin()](#getBottomMargin--) | 底部页面边距（仅用于 HTML 渲染） |
| [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | 设置 HTML 渲染的底部页面边距。 |
| [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | 此选项在渲染阿拉伯语、希伯来语、印度文字、拉丁系或西里尔系脚本时启用字距调整和其他 OpenType 功能。 |
| [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | 此选项在渲染阿拉伯语、希伯来语、印度文字、拉丁系或西里尔系脚本时启用字距调整和其他 OpenType 功能。 |
| [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | 指示在渲染为 HTML 或 PDF 时是否应禁用目录导航。 |
| [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | 设置在渲染为 HTML 或 PDF 时是否应禁用目录导航。 |
| [isUpdateFields()](#isUpdateFields--) | 获取一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前是否应更新某些类型的字段。 |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | 设置一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前是否应更新某些类型的字段。 |
| [equals(Object o)](#equals-java.lang.Object-) | 检查选项是否已更改。 |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


初始化 WordProcessingOptions 类的新实例。包含用于渲染文字处理文档的选项。详情请参阅 [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


检索用于渲染 HTM 和 HTML 文件的页面大小。

使用默认页面尺寸时，某些内容可能无法适应页面框架。要适配内容，您可以使用 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) 设置更大的页面尺寸，例如 A3。

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


设置用于渲染 HTM 和 HTML 文件的页面大小。

使用默认页面尺寸时，某些内容可能无法适应页面框架。要适配内容，您可以使用 [PageSize.A3](../../com.groupdocs.viewer.options/pagesize\#A3) 设置更大的页面尺寸，例如 A3。

***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize\#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | 输出页面的尺寸。 |

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


指示是否已启用对已跟踪更改（修订）的渲染。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Returns:**
boolean -  true  如果已启用已跟踪更改的渲染，  false  否则。
### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


设置是否启用对已跟踪更改（修订）的渲染。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true  启用已跟踪更改的渲染，  false  禁用它。 |

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


检索 HTML 渲染的左页边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 左侧页面边距值。
### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


设置 HTML 渲染的左页边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| leftMargin | java.lang.Double | 要设置的左侧页面边距值。 |

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


获取 HTML 渲染的右页边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 右侧页面边距值。
### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


设置 HTML 渲染的右页边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rightMargin | java.lang.Double | 要设置的右侧页面边距值。 |

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


检索 HTML 渲染的顶部页边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 顶部页面边距。
### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


设置 HTML 渲染的顶部页面边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| topMargin | java.lang.Double | 要设置的顶部页面边距。 |

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


底部页面边距（仅用于 HTML 渲染）

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Returns:**
java.lang.Double - 底部页面边距。
### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


设置 HTML 渲染的底部页面边距。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bottomMargin | java.lang.Double | 要设置的底部页面边距。 |

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


此选项在渲染阿拉伯语、希伯来语、印度文字、拉丁系或西里尔系脚本时启用字距调整和其他 OpenType 功能。

**Returns:**
boolean - True 如果已启用 OpenType 功能，false 否则。
### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


此选项在渲染阿拉伯语、希伯来语、印度文字、拉丁系或西里尔系脚本时启用字距调整和其他 OpenType 功能。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| enableOpenTypeFeatures | boolean | 若要启用 OpenType 功能，请设为 true，否则为 false。 |

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


指示在渲染为 HTML 或 PDF 时是否应禁用目录导航。若将此选项设为 true，则在 HTML 渲染时，目录中的相对链接将被 span 标签替代，虽然功能被移除但保持视觉外观。对于 PDF 渲染，目录将以纯文本形式呈现，不包含链接。

**Returns:**
boolean - 若目录导航被禁用则为 True；否则为 false。
### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


设置在渲染为 HTML 或 PDF 时是否应禁用目录导航。若将此选项设为 true，则在 HTML 渲染时，目录中的相对链接将被 span 标签替代，虽然功能被移除但保持视觉外观。对于 PDF 渲染，目录将以纯文本形式呈现，不包含链接。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| unlinkTableOfContents | boolean | 指示是否应禁用目录导航。 |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


获取一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前，是否应更新某些类型的字段。此属性的默认值为 true \\u2014 字段将在保存前被更新。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


设置一个值，用于确定在将输入的 WordProcessing 文档保存为 HTML、PDF、PNG 或 JPEG 输出格式之前，是否应更新某些类型的字段。此属性的默认值为 true \\u2014 字段将在保存前被更新。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| updateFields | boolean |  |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


检查选项是否已更改。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| o | java.lang.Object | 用于比较相等性的对象。 |

**Returns:**
boolean - 若选项等于指定对象则为 true，否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


计算此对象的哈希码值。哈希码基于对象的内部状态，并用于哈希映射和哈希集合等基于哈希的数据结构。

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - 此对象的哈希码值。
