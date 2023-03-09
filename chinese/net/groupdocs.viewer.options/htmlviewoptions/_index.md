---
title: HtmlViewOptions
second_title: GroupDocs.Viewer for .NET API 参考
description: 提供将文档呈现为 HTML 格式的选项
type: docs
weight: 330
url: /zh/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

提供将文档呈现为 HTML 格式的选项。

```csharp
public class HtmlViewOptions : ViewOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 存档文件视图选项。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 绘图视图选项。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 找不到文档中使用的特定字体时使用的默认字体。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 电子邮件消息查看选项。 |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | 启用后可防止将任何字体添加到 HTML 文档中。 |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | 字体名称列表，要从 HTML 文档中排除。 |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 表示是否为打印优化输出 HTML。 |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 输出图像的高度（以像素为单位）。 （仅将单个图像转换为 HTML 时） |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 输出图像的最大高度（以像素为单位）。 （仅将单个图像转换为 HTML 时） |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 输出图像的最大宽度（以像素为单位）。 （仅将单个图像转换为 HTML 时） |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 输出图像的宽度（以像素为单位）。 （仅将单个图像转换为 HTML 时） |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 邮件存储数据文件查看选项。 |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | 启用 HTML 内容和 HTML 资源缩小。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | MS Outlook 数据文件视图选项。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 文档查看选项。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 演示文稿处理文档视图选项。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 项目管理文件视图选项。 |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | 启用渲染注释。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 启用隐藏页面的呈现。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 启用渲染注释。 |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | 启用响应式渲染； 响应式网页在具有不同屏幕尺寸的设备上呈现良好。 |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | 允许将整个文档呈现为一个 HTML 文件。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 电子表格文件视图选项。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 文本文件拆分为页面选项。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio 文件处理文档视图选项。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 应用于每个页面的文本水印。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | 此呈现选项使您能够在呈现 Web 文档时自定义 输出 HTML/PDF/PNG/JPEG 的外观。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 此呈现选项使您能够在呈现 Word 文档时自定义 输出 HTML/PDF/PNG/JPEG 的外观。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)类. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于呈现为具有嵌入式资源的 HTML 的类。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于呈现为具有嵌入式资源的 HTML 的类。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)类. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于呈现为具有嵌入式资源的 HTML 的类。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)类. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)类. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | 初始化新实例[`HtmlViewOptions`](../htmlviewoptions)用于使用外部资源呈现为 HTML 的类。 |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | 对页面应用顺时针旋转。 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | 页面旋转。 |

### 也可以看看

* class [ViewOptions](../viewoptions)
* 命名空间 [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* 部件 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
