---
title: "功能概览"
linkTitle: "Features overview"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "使用 GroupDocs.Viewer for Python via .NET 将文档渲染为 HTML、PDF、PNG 或 JPEG；提取文本；列出附件；并应用旋转、重新排序和水印。"
type: docs
url: /zh/python-net/guides/features-overview/
is_root: false
weight: 30
---


## Rendering Documents

GroupDocs.Viewer 中的术语 *rendering* 描述了将文档转换为保留页面边界的文件格式的过程。例如，当一个三页的 DOCX 文件渲染为 HTML 时，结果是三个 HTML 文件——每页一个。请参阅 [Developer Guide]() 获取可运行的示例。

![Rendering diagram](https://docs.groupdocs.com/viewer/python-net/images/getting-started/features-overview/rendering.png)

### Rendering to HTML

当您需要时，渲染为 HTML 是最佳选择：

- Build a web-based application and display document content inside a browser.
- Allow users to interact with the rendered text — select, copy, or search it.
- View document pages separately.
- Zoom in on a document without quality loss.
- Rotate, reorder, or watermark pages.

GroupDocs.Viewer for Python 提供两种 HTML 资源管理模式：

- **HTML with external resources** — stores page resources (CSS, fonts, images) next to the HTML file so common resources are reused across pages. Reduces overall page size and speeds up loading.
- **HTML with embedded resources** — inlines every resource into the HTML file so each page is self-contained. Larger individual files but easier to distribute.

### Rendering to PNG or JPEG

当您需要时，渲染为 PNG 或 JPEG 是最佳选择：

- Support any type of application (desktop, web, mobile, CLI).
- Restrict interaction with rendered text — for example, to prevent copying. You can still extract a text layer separately if you want to overlay selectable text on the image.
- View document pages separately.
- Rotate, reorder, or watermark pages.

两种图像格式的快速比较：

- **PNG** is a lossless raster format that supports full-colour images and transparency. PNG does not expose a quality setting. It is a good choice for line drawings, text, and iconic graphics at small file sizes.
- **JPEG** is a lossy compressed format whose quality can be tuned — lowering the quality removes detail and adds noise, but the file becomes smaller. JPEG is optimal for photographs and any image with a large colour range, and is a common web choice thanks to its compression ratio.

### Rendering to PDF

GroupDocs.Viewer 将文档渲染为单个 PDF 文件。当您需要时，渲染为 PDF 是最佳选择：

- Print documents.
- Send documents via email.
- Distribute all pages as a single file rather than a collection of per-page files.

## Retrieving Document Information

GroupDocs.Viewer for Python 在不渲染的情况下公开源文档的基本信息——文件类型、页数、带坐标的文本等。请参阅 [Get Document Info]().

还可获取特定格式的信息：

- **Archive** — list of folders contained in the archive.
- **CAD** — list of layers and layouts in a CAD document.
- **Email** — list of folders contained in an Outlook data file.
- **PDF** — a flag that indicates whether document printing is allowed.
- **Project Management** — project start and end dates.

### Text extraction

在渲染为 PNG 或 JPEG 时，您可以选择提取文档文本。文本会连同每个单词的坐标一起返回，这在在页面图像上叠加可选择的文本层时非常有用。

## Processing Attachments

在 GroupDocs.Viewer 中，*attachments* 包括电子邮件附件、嵌入 PDF 的文件以及压缩归档中的各个项目。

使用 GroupDocs.Viewer，您可以列出并保存：

- Email attachments.
- Files embedded in PDF documents.
- Email messages contained in Outlook and Lotus Notes data files.
- Individual files inside archive containers.

请参阅 [Processing Attachments]() 获取可运行的示例。

## Output Transformation

GroupDocs.Viewer for Python 附带一组选项，用于转换每个渲染的页面：

- **Rotate pages** — change page orientation when rendering to HTML, JPG, PNG, or PDF.
- **Add a text watermark** — stamp a text watermark on every rendered page.
- **Reorder pages** — render pages in any order you prefer, including when rendering to PDF.

## Caching Results

GroupDocs.Viewer for Python 支持缓存，以加速重复渲染并降低应用程序的整体负载。

默认情况下，缓存存储在本地磁盘上。viewer API 还公开了缓存接口，可用于实现第三方存储——FTP、Amazon S3、Dropbox、Google Drive、Microsoft Azure、Redis 或任何其他后端。
