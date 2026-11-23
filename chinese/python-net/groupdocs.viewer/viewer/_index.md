---
title: "Viewer 类"
second_title: "GroupDocs.Viewer 用于 Python，通过 .NET API 参考"
description: "表示控制文档渲染过程的主类。"
type: docs
url: /zh/python-net/groupdocs.viewer/viewer/
is_root: false
weight: 100
---


## Viewer class

表示控制文档渲染过程的主类。

Viewer 类型公开以下成员：

### 构造函数
| 构造函数 | 描述 |
| :- | :- |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-settings) | 初始化一个新的 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#get_file_stream-get_load_options-settings) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-leave_open) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-leave_open) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-settings-leave_open) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings) | 初始化一个新的 Viewer 实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#stream-load_options-settings-leave_open) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-settings) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 类的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options) | 初始化 [`Viewer`](/viewer/python-net/groupdocs.viewer/viewer/) 的新实例。 |
| [__init__](/viewer/python-net/groupdocs.viewer/viewer/__init__/#file_path-load_options-settings) | 初始化一个新的 Viewer 实例。 |

### 方法
| 方法 | 描述 |
| :- | :- |
| [dispose](/viewer/python-net/groupdocs.viewer/viewer/dispose/) | 释放文件流和受管理的内部资源。 |
| [get_all_fonts](/viewer/python-net/groupdocs.viewer/viewer/get_all_fonts/) | 返回已加载文档中使用的所有字体，包括嵌入的字体和操作系统上已安装的系统字体。 |
| [get_attachments](/viewer/python-net/groupdocs.viewer/viewer/get_attachments/) | 返回文档中包含的附件。 |
| [get_file_info](/viewer/python-net/groupdocs.viewer/viewer/get_file_info/) | 返回关于文件的信息，例如文件类型以及指示文件是否加密的标志。 |
| [get_view_info](/viewer/python-net/groupdocs.viewer/viewer/get_view_info/#options) | 返回视图和文档特定的信息。 |
| [get_view_info_view_info_options](/viewer/python-net/groupdocs.viewer/viewer/get_view_info_view_info_options/) |  |
| [save_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment/#attachment-destination) | 将附件文件保存到 `destination` 流。 |
| [save_attachment_attachment](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_attachment/) |  |
| [save_attachment_stream](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_stream/) |  |
| [save_attachment_streams](/viewer/python-net/groupdocs.viewer/viewer/save_attachment_streams/) |  |
| [search](/viewer/python-net/groupdocs.viewer/viewer/search/#options) | 执行文本搜索，并根据提供的选项在已加载的文档中高亮显示找到的文本。 |
| [search_search_highlight_options](/viewer/python-net/groupdocs.viewer/viewer/search_search_highlight_options/) |  |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options) | 创建所有文档页面的视图。 |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-page_numbers) | 创建特定文档页面的视图。 |
| [view](/viewer/python-net/groupdocs.viewer/viewer/view/#options-cancellation_token-page_numbers) | 创建特定文档页面的视图。 |
| [view_view_options](/viewer/python-net/groupdocs.viewer/viewer/view_view_options/) |  |

### 示例

```python
from groupdocs.viewer import Viewer
from groupdocs.viewer.options import HtmlViewOptions, PngViewOptions

# 将 DOCX 渲染为 HTML
with Viewer("./sample.docx") as viewer:
    html_opts = HtmlViewOptions.for_embedded_resources("page_{0}.html")
    viewer.view(html_opts)

# 将 PDF 渲染为 PNG
with Viewer("document.pdf") as viewer:
    png_opts = PngViewOptions("page_{0}.png")
    viewer.view(png_opts)
```

### Guides
使用 `Viewer` 的任务指南：

* [Quick Start Guide](/viewer/python-net/guides/quick-start-guide/)
* [Get Document Information](/viewer/python-net/guides/get-document-info/)
* [Load document from local disk](/viewer/python-net/guides/load-document-from-local-disk/)
* [Load document from stream](/viewer/python-net/guides/load-document-from-stream/)
* [Load document from URL](/viewer/python-net/guides/load-document-from-url/)
* [Add text watermarks](/viewer/python-net/guides/add-text-watermark/)
* [Protect PDF document](/viewer/python-net/guides/protect-pdf-document/)
* [Reorder pages](/viewer/python-net/guides/reorder-pages/)
* [Save attachments](/viewer/python-net/guides/how-to-extract-and-save-attachments/)

### 另见
* module [`groupdocs.viewer`](/viewer/python-net/groupdocs.viewer/)
