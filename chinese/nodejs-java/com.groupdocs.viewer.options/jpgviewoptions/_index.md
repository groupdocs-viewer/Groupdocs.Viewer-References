---
title: "JpgViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供将文档渲染为 JPG 格式的选项。"
type: docs
weight: 17
url: /zh/nodejs-java/com.groupdocs.viewer.options/jpgviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)

**All Implemented Interfaces:**
[com.groupdocs.viewer.options.IMaxSizeOptions](../../com.groupdocs.viewer.options/imaxsizeoptions)
```
public class JpgViewOptions extends ViewOptions implements IMaxSizeOptions
```

提供将文档渲染为 JPG 格式的选项。

JpgViewOptions 类封装了可用于在 GroupDocs.Viewer 组件中控制文档渲染为 JPG 格式的附加设置和参数。

示例用法：

```

 JpgViewOptions options = new JpgViewOptions();
 options.setMaxWidth(1920);
 options.setMaxHeight(1080);
 options.setQuality((byte) 96);
 options.setRenderComments(true);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(options);
     // Use the viewer object for further operations
 }
 
```

***Note:** The JpgViewOptions class implements the IMaxSizeOptions interface to specify the maximum size of the output JPG images.*
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [JpgViewOptions(CreatePageStream createPageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-) | 初始化 JpgViewOptions 类的新实例。 |
| [JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)](#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-) | 初始化 JpgViewOptions 类的新实例。 |
| [JpgViewOptions(PageStreamFactory pageStreamFactory)](#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-) | 初始化 JpgViewOptions 类的新实例。 |
| [JpgViewOptions()](#JpgViewOptions--) | 使用 "p\_\{0\}.jpg" 作为输出文件的文件路径格式，初始化 JpgViewOptions 的新实例。 |
| [JpgViewOptions(String filePathFormat)](#JpgViewOptions-java.lang.String-) | 初始化 JpgViewOptions 类的新实例。 |
| [JpgViewOptions(Path filePathFormat)](#JpgViewOptions-java.nio.file.Path-) | 初始化 JpgViewOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMaxWidth()](#getMaxWidth--) | 获取输出图像的最大宽度（像素）。 |
| [setMaxWidth(int maxWidth)](#setMaxWidth-int-) | 设置输出图像的最大宽度（像素）。 |
| [getMaxHeight()](#getMaxHeight--) | 获取输出图像的最大高度（像素）。 |
| [setMaxHeight(int maxHeight)](#setMaxHeight-int-) | 设置输出图像的最大高度（像素）。 |
| [getQuality()](#getQuality--) | 获取输出图像的质量。 |
| [setQuality(byte value)](#setQuality-byte-) | 设置输出图像的质量。 |
| [isExtractText()](#isExtractText--) | 启用文本提取。 |
| [setExtractText(boolean value)](#setExtractText-boolean-) | 启用或禁用文本提取。 |
| [getWidth()](#getWidth--) | 获取输出图像的宽度（像素）。 |
| [setWidth(int value)](#setWidth-int-) | 设置输出图像的宽度（像素）。 |
| [getHeight()](#getHeight--) | 获取输出图像的高度（像素）。 |
| [setHeight(int value)](#setHeight-int-) | 设置输出图像的高度（以像素为单位）。 |
| [getPageStreamFactory()](#getPageStreamFactory--) | 获取实现创建和释放输出页面流方法的工厂。 |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | 获取用于估计 Word 或 Email 文档保存进度的回调。 |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | 设置用于估计 Word 或 Email 文档保存进度的回调。 |
### JpgViewOptions(CreatePageStream createPageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream)
```


初始化 JpgViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 该方法实例化用于写入输出页面数据的流。 |

### JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream) {#JpgViewOptions-com.groupdocs.viewer.interfaces.CreatePageStream-com.groupdocs.viewer.interfaces.ReleasePageStream-}
```
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```


初始化 JpgViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | [CreatePageStream](../../com.groupdocs.viewer.interfaces/createpagestream) | 该方法实例化用于写入输出页面数据的流。 |
| releasePageStream | [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) | 释放由传递给 createPageStream 参数的委托分配的方法创建的流的方法。 |

### JpgViewOptions(PageStreamFactory pageStreamFactory) {#JpgViewOptions-com.groupdocs.viewer.interfaces.PageStreamFactory-}
```
public JpgViewOptions(PageStreamFactory pageStreamFactory)
```


初始化 JpgViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) | 实现创建和释放输出页面流方法的工厂。 |

### JpgViewOptions() {#JpgViewOptions--}
```
public JpgViewOptions()
```


使用 "p\_\{0\}.jpg" 作为输出文件的文件路径格式，初始化 JpgViewOptions 的新实例。输出文件将放置在应用程序的当前工作目录中。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

### JpgViewOptions(String filePathFormat) {#JpgViewOptions-java.lang.String-}
```
public JpgViewOptions(String filePathFormat)
```


初始化 JpgViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.lang.String | 文件路径格式，例如 'page\_\{0\}.jpg'。 |

### JpgViewOptions(Path filePathFormat) {#JpgViewOptions-java.nio.file.Path-}
```
public JpgViewOptions(Path filePathFormat)
```


初始化 JpgViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/#rendering-to-jpeg

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filePathFormat | java.nio.file.Path | 文件路径格式，例如 'page\_\{0\}.jpg'。 |

### getMaxWidth() {#getMaxWidth--}
```
public int getMaxWidth()
```


获取输出图像的最大宽度（像素）。

使用此属性设置最大输出图像宽度（像素）。有关代码示例，请参阅[文档][]. 如果您设置了 \#setWidth(int).setWidth(int) 属性，则此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 输出图像的最大宽度。
### setMaxWidth(int maxWidth) {#setMaxWidth-int-}
```
public void setMaxWidth(int maxWidth)
```


设置输出图像的最大宽度（像素）。

使用此属性设置最大输出图像宽度（像素）。有关代码示例，请参阅[文档][]. 如果您设置了 \#setWidth(int).setWidth(int) 属性，则此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxWidth | int | 输出图像的最大宽度。 |

### getMaxHeight() {#getMaxHeight--}
```
public int getMaxHeight()
```


获取输出图像的最大高度（像素）。

使用此属性设置最大输出图像高度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置了 \#setHeight(int).setHeight(int) 属性，则此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Returns:**
int - 输出图像的最大高度。
### setMaxHeight(int maxHeight) {#setMaxHeight-int-}
```
public void setMaxHeight(int maxHeight)
```


设置输出图像的最大高度（像素）。

使用此属性设置最大输出图像高度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置了 \#setHeight(int).setHeight(int) 属性，则此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/set-image-size-limits-when-rendering-to-png-jpg/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| maxHeight | int | 输出图像的最大高度。 |

### getQuality() {#getQuality--}
```
public final byte getQuality()
```


获取输出图像的质量。

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Returns:**
byte - 输出图像的质量。
### setQuality(byte value) {#setQuality-byte-}
```
public final void setQuality(byte value)
```


设置输出图像的质量。

***Note:** Use this property to adjust images quality. The value must be between 1 (minimum quality) and 100. The default value is 90.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-quality-for-jpg/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte | 输出图像的质量。 |

### isExtractText() {#isExtractText--}
```
public final boolean isExtractText()
```


启用文本提取。

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Returns:**
boolean -  true  如果启用了文本提取，则为 true，  false  否则。
### setExtractText(boolean value) {#setExtractText-boolean-}
```
public final void setExtractText(boolean value)
```


启用或禁用文本提取。

***Note:** Use this property to get the text contained in a source document and its coordinates. Then you can use this data to add a selectable text over the image or to implement a text search in image-based rendering.* For code example, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-get-text-coordinates/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | true  启用文本提取，  false  禁用。 |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


获取输出图像的宽度（像素）。

使用此属性设置输出图像宽度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置此属性，则 \#setMaxWidth(int).setMaxWidth(int) 属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 输出图像的宽度。
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


设置输出图像的宽度（像素）。

使用此属性设置输出图像宽度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置此属性，则 \#setMaxWidth(int).setMaxWidth(int) 属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 输出图像的宽度。 |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


获取输出图像的高度（像素）。

使用此属性设置输出图像高度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置此属性，则 \#setMaxHeight(int).setMaxHeight(int) 属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Returns:**
int - 输出图像的高度。
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


设置输出图像的高度（以像素为单位）。

使用此属性设置输出图像高度（以像素为单位）。有关代码示例，请参阅[documentation][]. 如果设置此属性，则 \#setMaxHeight(int).setMaxHeight(int) 属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/java/image-viewer-adjust-image-size/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 输出图像的高度。 |

### getPageStreamFactory() {#getPageStreamFactory--}
```
public final PageStreamFactory getPageStreamFactory()
```


获取实现创建和释放输出页面流方法的工厂。

**Returns:**
[PageStreamFactory](../../com.groupdocs.viewer.interfaces/pagestreamfactory) - the factory for the output page stream.
### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


获取用于估计 Word 或 Email 文档保存进度的回调。

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 用于估计文档保存进度的回调。
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


设置用于估计 Word 或 Email 文档保存进度的回调。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 用于估计文档保存进度的回调。 |

