---
title: "PdfViewOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API 参考"
description: "提供将文档渲染为 PDF 格式的选项。"
type: docs
weight: 23
url: /zh/nodejs-java/com.groupdocs.viewer.options/pdfviewoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.viewer.options.BaseViewOptions](../../com.groupdocs.viewer.options/baseviewoptions), [com.groupdocs.viewer.options.ViewOptions](../../com.groupdocs.viewer.options/viewoptions)
```
public class PdfViewOptions extends ViewOptions
```

提供将文档渲染为 PDF 格式的选项。

PdfViewOptions 类封装了可用于控制文档在 GroupDocs.Viewer 组件中渲染为 PDF 格式的附加设置和参数。详情请参阅 [documentation][].

示例用法：

```

 PdfViewOptions pdfViewOptions = new PdfViewOptions();
 pdfViewOptions.setImageHeight(256);
 pdfViewOptions.setImageWidth(128);
 pdfViewOptions.setDefaultFontName("font-name");

 try (Viewer viewer = new Viewer("document.pdf")) {
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
```


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfViewOptions(CreateFileStream createFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-) | 初始化 PdfViewOptions 类的新实例。 |
| [PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)](#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-) | 初始化 PdfViewOptions 类的新实例。 |
| [PdfViewOptions(FileStreamFactory fileStreamFactory)](#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-) | 初始化 PdfViewOptions 类的新实例。 |
| [PdfViewOptions()](#PdfViewOptions--) | 使用默认设置初始化 PdfViewOptions 类的新实例。 |
| [PdfViewOptions(String outputFilePath)](#PdfViewOptions-java.lang.String-) | 初始化 PdfViewOptions 类的新实例。 |
| [PdfViewOptions(Path outputFilePath)](#PdfViewOptions-java.nio.file.Path-) | 初始化 PdfViewOptions 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPdfOptimizationOptions()](#getPdfOptimizationOptions--) | 通过使用不同选项的优化技术来减小输出 PDF 文件的大小。 |
| [setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)](#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-) | 通过使用不同选项的优化技术来减小输出 PDF 文件的大小。 |
| [getImageMaxWidth()](#getImageMaxWidth--) | 检索输出图像的最大宽度（像素）。 |
| [setImageMaxWidth(int imageMaxWidth)](#setImageMaxWidth-int-) | 设置输出图像的最大宽度（像素）。 |
| [getImageMaxHeight()](#getImageMaxHeight--) | 检索输出图像的最大高度（像素）。 |
| [setImageMaxHeight(int imageMaxHeight)](#setImageMaxHeight-int-) | 设置输出图像的最大高度（像素）。 |
| [getImageWidth()](#getImageWidth--) | 检索输出图像的宽度（像素）。 |
| [setImageWidth(int imageWidth)](#setImageWidth-int-) | 设置输出图像的宽度（像素）。 |
| [getImageHeight()](#getImageHeight--) | 检索输出图像的高度（以像素为单位）。 |
| [setImageHeight(int imageHeight)](#setImageHeight-int-) | 设置输出图像的高度（以像素为单位）。 |
| [getSecurity()](#getSecurity--) | 检索输出 PDF 文档的安全选项。 |
| [setSecurity(Security value)](#setSecurity-com.groupdocs.viewer.options.Security-) | 设置输出 PDF 文档的安全选项。 |
| [getDocumentSavingCallback()](#getDocumentSavingCallback--) | 检索用于估计保存 Word 或 Email 文档进度的回调函数。 |
| [setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)](#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-) | 设置用于估计保存 Word 或 Email 文档进度的回调函数。 |
### PdfViewOptions(CreateFileStream createFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream)
```


初始化 PdfViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) |  |

### PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream) {#PdfViewOptions-com.groupdocs.viewer.interfaces.CreateFileStream-com.groupdocs.viewer.interfaces.ReleaseFileStream-}
```
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```


初始化 PdfViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| createFileStream | [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) | 用于实例化用于写入输出文件数据的流的方法。 |
| releaseFileStream | [ReleaseFileStream](../../com.groupdocs.viewer.interfaces/releasefilestream) | 用于释放由 createFileStream 方法创建的流的方法。 |

### PdfViewOptions(FileStreamFactory fileStreamFactory) {#PdfViewOptions-com.groupdocs.viewer.interfaces.FileStreamFactory-}
```
public PdfViewOptions(FileStreamFactory fileStreamFactory)
```


初始化 PdfViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileStreamFactory | [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) | 实现创建和释放输出文件流方法的工厂。 |

### PdfViewOptions() {#PdfViewOptions--}
```
public PdfViewOptions()
```


使用默认设置初始化 PdfViewOptions 类的新实例。

此构造函数创建一个新的 PdfViewOptions 对象，使用 \"output.pdf\" 作为输出文件的路径格式。输出文件将放置在应用程序的当前工作目录中。有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

### PdfViewOptions(String outputFilePath) {#PdfViewOptions-java.lang.String-}
```
public PdfViewOptions(String outputFilePath)
```


初始化 PdfViewOptions 类的新实例。

此构造函数创建一个新的 PdfViewOptions 对象，使用指定的 outputFilePath 参数表示输出 PDF 文件的路径。有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFilePath | java.lang.String | 输出 PDF 文件的路径。 |

### PdfViewOptions(Path outputFilePath) {#PdfViewOptions-java.nio.file.Path-}
```
public PdfViewOptions(Path outputFilePath)
```


初始化 PdfViewOptions 类的新实例。

有关代码示例，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputFilePath | java.nio.file.Path | 输出 PDF 文件的路径。 |

### getPdfOptimizationOptions() {#getPdfOptimizationOptions--}
```
public PdfOptimizationOptions getPdfOptimizationOptions()
```


通过使用不同选项的优化技术来减小输出 PDF 文件的大小。

此选项支持所有可转换为 PDF 的输入文件格式：[Supported document formats][]。有关详细信息和代码示例，请参阅此 [page][] 及其子页面。


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) - PdfOptimizationOptions object or null.
### setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions) {#setPdfOptimizationOptions-com.groupdocs.viewer.options.PdfOptimizationOptions-}
```
public void setPdfOptimizationOptions(PdfOptimizationOptions pdfOptimizationOptions)
```


通过使用不同选项的优化技术来减小输出 PDF 文件的大小。

此选项支持所有可转换为 PDF 的输入文件格式：[Supported document formats][]。有关详细信息和代码示例，请参阅此 [page][] 及其子页面。


[Supported document formats]: https://docs.groupdocs.com/viewer/net/supported-document-formats/
[page]: https://docs.groupdocs.com/viewer/net/optimization-pdf-options/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdfOptimizationOptions | [PdfOptimizationOptions](../../com.groupdocs.viewer.options/pdfoptimizationoptions) | PdfOptimizationOptions 对象或 null。 |

### getImageMaxWidth() {#getImageMaxWidth--}
```
public int getImageMaxWidth()
```


检索输出图像的最大宽度（以像素为单位）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置最大输出图像宽度（以像素为单位）。GroupDocs.Viewer 在将单个图像渲染为 PDF 时会应用此属性。有关详细信息，请参阅[文档][]. 如果您设置了 property，此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 输出图像的最大宽度（以像素为单位）。
### setImageMaxWidth(int imageMaxWidth) {#setImageMaxWidth-int-}
```
public void setImageMaxWidth(int imageMaxWidth)
```


设置输出图像的最大宽度（以像素为单位）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置最大输出图像宽度（以像素为单位）。GroupDocs.Viewer 在将单个图像渲染为 PDF 时会应用此属性。有关详细信息，请参阅[文档][]. 如果您设置了 property，此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageMaxWidth | int | 输出图像的最大宽度（以像素为单位）。 |

### getImageMaxHeight() {#getImageMaxHeight--}
```
public int getImageMaxHeight()
```


检索输出图像的最大高度（以像素为单位）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置最大输出图像高度（以像素为单位）。GroupDocs.Viewer 在将单个图像渲染为 PDF 时会应用此属性。有关详细信息，请参阅[文档][]. 如果您设置了 property，此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 输出图像的最大高度（以像素为单位）。
### setImageMaxHeight(int imageMaxHeight) {#setImageMaxHeight-int-}
```
public void setImageMaxHeight(int imageMaxHeight)
```


设置输出图像的最大高度（单位：像素）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置最大输出图像高度（单位：像素）。GroupDocs.Viewer 仅在将单个图像渲染为 HTML 时应用此属性。有关详细信息，请参阅[documentation][]. 如果您设置了  property，此属性将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageMaxHeight | int | 输出图像的最大高度（单位：像素）。 |

### getImageWidth() {#getImageWidth--}
```
public int getImageWidth()
```


检索输出图像的宽度（单位：像素）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置输出图像宽度（单位：像素）。GroupDocs.Viewer 在将单个图像渲染为 PDF 时应用此属性。有关详细信息，请参阅[documentation][]. 如果您设置了此属性，the  property 将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 输出图像的宽度（单位：像素）。
### setImageWidth(int imageWidth) {#setImageWidth-int-}
```
public void setImageWidth(int imageWidth)
```


设置输出图像的宽度（单位：像素）。此参数仅在将单个图像转换为 PDF 时适用。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageWidth | int | 输出图像的宽度（单位：像素）。 |

### getImageHeight() {#getImageHeight--}
```
public int getImageHeight()
```


检索输出图像的高度（单位：像素）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置输出图像高度（单位：像素）。GroupDocs.Viewer 仅在将单个图像渲染为 HTML 时应用此属性。有关详细信息，请参阅[documentation][]. 如果您设置此属性，the  property 将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Returns:**
int - 输出图像的高度（单位：像素）。
### setImageHeight(int imageHeight) {#setImageHeight-int-}
```
public void setImageHeight(int imageHeight)
```


设置输出图像的高度（单位：像素）。此参数仅在将单个图像转换为 HTML 时适用。

使用此属性设置输出图像高度（单位：像素）。GroupDocs.Viewer 仅在将单个图像渲染为 HTML 时应用此属性。有关详细信息，请参阅[documentation][]. 如果您设置此属性，the  property 将被忽略。


[documentation]: https://docs.groupdocs.com/viewer/net/set-image-size-limits-when-rendering-to-pdf/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| imageHeight | int | 输出图像的高度（单位：像素）。 |

### getSecurity() {#getSecurity--}
```
public final Security getSecurity()
```


检索输出 PDF 文档的安全选项。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Returns:**
[Security](../../com.groupdocs.viewer.options/security) - the security options for the output PDF document.
### setSecurity(Security value) {#setSecurity-com.groupdocs.viewer.options.Security-}
```
public final void setSecurity(Security value)
```


设置输出 PDF 文档的安全选项。

有关详细信息，请参阅[文档][].


[documentation]: https://docs.groupdocs.com/viewer/net/protect-pdf-documents/

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Security](../../com.groupdocs.viewer.options/security) | 输出 PDF 文档的安全选项。 |

### getDocumentSavingCallback() {#getDocumentSavingCallback--}
```
public IDocumentSavingCallback getDocumentSavingCallback()
```


检索用于估计保存 Word 或 Email 文档进度的回调函数。

**Returns:**
com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback - 用于估计文档保存进度的回调。
### setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback) {#setDocumentSavingCallback-com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback-}
```
public void setDocumentSavingCallback(IDocumentSavingCallback documentSavingCallback)
```


设置用于估计保存 Word 或 Email 文档进度的回调函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentSavingCallback | com.groupdocs.viewer.domain.documents.converting.tohtml.utils.IDocumentSavingCallback | 用于估计文档保存进度的回调。 |

