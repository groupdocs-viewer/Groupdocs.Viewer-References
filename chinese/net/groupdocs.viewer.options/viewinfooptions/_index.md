---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer for .NET API 参考"
description: "包含检索视图信息的选项。"
type: docs
weight: 580
url: /zh/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

包含检索视图信息的选项。

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | 存档文件的视图选项。 |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD 绘图的视图选项。 |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | 设置文档的默认字体。 |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | 电子邮件消息的视图选项。 |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | 启用文本提取。 |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | 输出图像的高度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | 邮件存储数据文件的视图选项。 |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | 设置输出图像的最大高度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | 设置输出图像的最大宽度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook 数据文件的视图选项。 |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF 文档的视图选项。 |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | 演示文件的视图选项。 |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | 项目管理文件的视图选项。 |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | 当设置为 `true` 时禁用渲染评论。默认是 `false` — 显示所有评论。 |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | 启用隐藏页面的渲染。 |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | 为某些格式启用渲染注释和标注 |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | 电子表格文件的视图选项。 |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | 文本文件的视图选项。 |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio 文件的视图选项。 |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | Web 文件的视图选项。 |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | 输出图像的宽度（以像素为单位，仅用于渲染为 PNG/JPG）。 |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | 文字处理文件的视图选项。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 HTML 时检索视图信息。 |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 HTML 时检索视图信息。 |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 JPG 时检索视图信息。 |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 JPG 时检索视图信息。 |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 PDF 时检索视图信息。 |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 PNG 时检索视图信息。 |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | 初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例，以在渲染为 PNG 时检索视图信息。 |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | 基于 [`HtmlViewOptions`](../htmlviewoptions) 对象，初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例。 |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | 基于 [`JpgViewOptions`](../jpgviewoptions) 对象，初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例。 |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | 基于 [`PdfViewOptions`](../pdfviewoptions) 对象，初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例。 |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | 基于 [`PngViewOptions`](../pngviewoptions) 对象，初始化 [`ViewInfoOptions`](../viewinfooptions) 类的实例。 |

### 另见

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
