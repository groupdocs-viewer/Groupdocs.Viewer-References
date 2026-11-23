---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "包含将文档呈现为 HTML 格式的选项。有关详细信息，请参阅 topichttps//docs.groupdocs.com/viewer/net/renderingtohtml/ 及其子项。"
type: docs
weight: 320
url: /zh/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

包含将文档渲染为 HTML 格式的选项。详情请参阅[主题](https://docs.groupdocs.com/viewer/net/rendering-to-html/)及其子项。

```csharp
public class HtmlViewOptions : ViewOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 存档文件的视图选项。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 绘图的视图选项。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 设置文档的默认字体。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 电子邮件消息的视图选项。 |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | 禁用向 HTML 文档中添加任何字体。 |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | 要从 HTML 文档中排除的字体名称列表。 |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | 启用对输出 HTML 的打印优化。 |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | 输出图像的高度（像素）。此属性仅在将单个图像转换为 HTML 时可用。 |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | 输出图像的最大高度（像素）。此属性仅在将单个图像转换为 HTML 时可用。 |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | 输出图像的最大宽度（像素）。此属性仅在将单个图像转换为 HTML 时可用。 |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | 输出图像的宽度（像素）。此属性仅在将单个图像转换为 HTML 时可用。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 邮件存储数据文件的视图选项。 |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | 启用 HTML 内容和 HTML 资源的压缩。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook 数据文件的视图选项。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 文档的视图选项。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 演示文件的视图选项。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 项目管理文件的视图选项。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | 当设置为 `true` 时禁用渲染评论。默认是 `false` — 显示所有评论。 |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | 在渲染包含脚本的输入文档时，允许从生成的 HTML 文档中的链接中移除 JavaScript 源代码。默认已启用（`true`）。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 启用隐藏页面的渲染。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 为某些格式启用渲染注释和标注 |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | 启用响应式渲染。 |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | 启用将整个文档渲染为单个 HTML 文件。 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 电子表格文件的视图选项。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 文本文件的视图选项。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio 文件的视图选项。 |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | 要应用于每页的文字水印。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web 文件的视图选项。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 文字处理文件的视图选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带嵌入资源的 HTML。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带嵌入资源的 HTML。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例。 |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带嵌入资源的 HTML。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带外部资源的 HTML。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带外部资源的 HTML。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例。 |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | 初始化 [`HtmlViewOptions`](../htmlviewoptions) 类的实例，以渲染为带外部资源的 HTML。 |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | 对页面应用顺时针旋转。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | 页面旋转。 |

### 另见

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
